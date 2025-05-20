# Function: <code>nlmsg_end</code>

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
In kernel/taskstats.c (ffffffff8113e1a6)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - kernel/taskstats.c:send_reply
  - kernel/taskstats.c:taskstats_exit
```
```
In fs/quota/netlink.c (ffffffff8127685a)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81489801)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8168591e)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff8170fe2a)
Location: include/net/netlink.h:497
Inline: True
```
```
In net/core/neighbour.c (ffffffff81726788)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8172d25a)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/core/fib_rules.c (ffffffff81739e88)
Location: include/net/netlink.h:497
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8174fd0e)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_ctrl_event
```
```
In net/ipv4/route.c (ffffffff81753e3f)
Location: include/net/netlink.h:497
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8178174c)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff817902fc)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8179db2b)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff817a880b)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff817cb8f3)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff817d25a5)
Location: include/net/netlink.h:497
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d89f2)
Location: include/net/netlink.h:497
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff817dfb8e)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff817f934d)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81809df4)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d47f)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e5e6)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180fdce)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81813ec0)
Location: include/net/netlink.h:497
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff811473bf)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff812a30a6)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff814d85fb)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff816e6e02)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff8177776a)
Location: include/net/netlink.h:508
Inline: True
```
```
In net/core/neighbour.c (ffffffff81790ef9)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81799300)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817a6188)
Location: include/net/netlink.h:508
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff817bc4a1)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff817bfedf)
Location: include/net/netlink.h:508
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817eec09)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff817fde6b)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b695)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81815f3b)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8183891b)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff81840065)
Location: include/net/netlink.h:508
Inline: True
```
```
In net/ipv6/route.c (ffffffff818423da)
Location: include/net/netlink.h:508
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff8184f2f7)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/ip6mr.c (ffffffff81868b8d)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff8187b8f4)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187f870)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880c67)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8188249d)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8188349d)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81886da0)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/switchdev/switchdev.c (ffffffff8188ae27)
Location: include/net/netlink.h:508
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
In kernel/taskstats.c (ffffffff8115125f)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff812b8a86)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff814face3)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81716252)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff817a47ea)
Location: include/net/netlink.h:508
Inline: True
```
```
In net/core/neighbour.c (ffffffff817be73c)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff817c70b0)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817d4ce8)
Location: include/net/netlink.h:508
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff817ebdb1)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff817f308b)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f619)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff8182edcb)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c7ae)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff818476eb)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8186a44b)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff81871ce5)
Location: include/net/netlink.h:508
Inline: True
```
```
In net/ipv6/route.c (ffffffff81874132)
Location: include/net/netlink.h:508
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff8188124d)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81899913)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff8189b9dd)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff818b01b4)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b4120)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b5517)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6d4d)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7d3d)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff818bb610)
Location: include/net/netlink.h:508
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/switchdev/switchdev.c (ffffffff818bf1f7)
Location: include/net/netlink.h:508
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
In kernel/taskstats.c (ffffffff811538dc)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff812c5e52)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8150a21d)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8172e052)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff817c292a)
Location: include/net/netlink.h:517
Inline: True
```
```
In net/core/neighbour.c (ffffffff817dd7e7)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff817e59a3)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817f4033)
Location: include/net/netlink.h:517
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8180a41f)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8180bced)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81813a2e)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff81840323)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff8184f2c5)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8185deca)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff8186ac3f)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8188e9a1)
Location: include/net/netlink.h:517
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
In net/ipv6/addrlabel.c (ffffffff81896a65)
Location: include/net/netlink.h:517
Inline: True
```
```
In net/ipv6/route.c (ffffffff8189903d)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff818a72ef)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff818bfb23)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff818c1da3)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff818d6b72)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818daad0)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dbe6b)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd62c)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de62c)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff818e1fe3)
Location: include/net/netlink.h:517
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/switchdev/switchdev.c (ffffffff818e5b2d)
Location: include/net/netlink.h:517
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
In kernel/taskstats.c (ffffffff811600dc)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff812e9d02)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8154c71d)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8179f682)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff8183c26a)
Location: include/net/netlink.h:523
Inline: True
```
```
In net/core/neighbour.c (ffffffff81857b67)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81860a46)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8186f798)
Location: include/net/netlink.h:523
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8188944c)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8188ac7d)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81893091)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf6c3)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff818ceef5)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff818ddefa)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff818eb409)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8190fff1)
Location: include/net/netlink.h:523
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
In net/ipv6/addrlabel.c (ffffffff81917ed4)
Location: include/net/netlink.h:523
Inline: True
```
```
In net/ipv6/route.c (ffffffff8191a343)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81929d51)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81942bf3)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff819456e3)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff8195c742)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819606b0)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961a4b)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8196321c)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8196422c)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81967d85)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/taskstats.c (ffffffff8116f01c)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff81316c06)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81582e5d)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff817e6c62)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff81886cca)
Location: include/net/netlink.h:523
Inline: True
```
```
In net/core/neighbour.c (ffffffff818a2ca9)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818aa91b)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818c0fd4)
Location: include/net/netlink.h:523
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818dce29)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff818de2cb)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff818e7178)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff819152ae)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81925cb8)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819348dd)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81941c8e)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81967401)
Location: include/net/netlink.h:523
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
In net/ipv6/addrlabel.c (ffffffff8196f594)
Location: include/net/netlink.h:523
Inline: True
```
```
In net/ipv6/route.c (ffffffff819721fa)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81981d80)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff8199bb2a)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff8199d1d2)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819b5f22)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819b9e70)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb1bb)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bca6c)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bdacc)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819c15be)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cb101)
Location: include/net/netlink.h:523
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff8117cb1c)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff8132dbb6)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8159af8d)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81813012)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff818a73c9)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff818c5a8e)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818d07b8)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818e9de1)
Location: include/net/netlink.h:666
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819097ff)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8190ac8b)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81914056)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_metrics.c (ffffffff819438ce)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81954c54)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8196422a)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff819715fb)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8199ca0e)
Location: include/net/netlink.h:666
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
In net/ipv6/addrlabel.c (ffffffff819a5121)
Location: include/net/netlink.h:666
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a7952)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff819b8429)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff819d26fa)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff819d3d2f)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819ed1e2)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1140)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f242b)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3cbc)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4c6c)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819f8b11)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a042a8)
Location: include/net/netlink.h:666
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff811899cd)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff813558f2)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815cc608)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff818550b0)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff818f2469)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81911ab0)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8191d64b)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81939844)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/core/devlink.c (ffffffff81951ac7)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffffffff8196ab49)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8196c076)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81971240)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7ea1)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff819b8bc4)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819c9e69)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff819d3814)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff819dad74)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a08be7)
Location: include/net/netlink.h:900
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
In net/ipv6/addrlabel.c (ffffffff81a115c1)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a13fac)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a26e97)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a414f3)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a41fae)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a5c3d7)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a603fc)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a6177a)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a6311b)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a6412b)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a68073)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a7354e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff81195910)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff8136dc32)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815ed888)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81886b10)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff819243b9)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81944120)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8194fc8f)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8196c711)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81976566)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81983b0e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffffffff819a159f)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff819a2a26)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819a7c5e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819def34)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff819ef8c4)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00a29)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81a0a384)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a11c3a)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a3f2f7)
Location: include/net/netlink.h:900
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
In net/ipv6/addrlabel.c (ffffffff81a481e1)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4ab9c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a5d8fb)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a78173)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a78c0e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a93004)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a9702c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a9834a)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a99ccd)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9acad)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a9e9d3)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa9d3e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff811aa96f)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:send_cpu_listeners
```
```
In fs/quota/netlink.c (ffffffff813b5762)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81699408)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff819f8089)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81a14192)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81a214cb)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a405c5)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a4b2ff)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81a5f705)
Location: include/net/netlink.h:952
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
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffffffff81a7af72)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81a7c76a)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a867f7)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81a89f86)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a8cbb1)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ipv4/route.c (ffffffff81a913c7)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc520)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81addd0c)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81aefcb0)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81afaee7)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b04b72)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b34f77)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f081)
Location: include/net/netlink.h:952
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b45103)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81b53c0f)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81b72152)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81b74651)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b8e315)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b928ac)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93e37)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9551d)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b9647d)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81b997c1)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5f3e)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb368b)
Location: include/net/netlink.h:952
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
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
In kernel/taskstats.c (ffffffff811a7f1f)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:send_cpu_listeners
```
```
In fs/quota/netlink.c (ffffffff813c6f92)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff816b6525)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f73a)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff819f7ae9)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81a1443a)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81a1fa5b)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a432c5)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a50f2f)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81a67ef5)
Location: include/net/netlink.h:965
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
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffffffff81a83d6c)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81a85a66)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a90107)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81a93856)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a962c8)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81a97790)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/route.c (ffffffff81a9b248)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad84ed)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81aeaaec)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81afcbf0)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81b085b7)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b12ce2)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b43b9c)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b4db01)
Location: include/net/netlink.h:965
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b53aa6)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81b621ff)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81b80eb2)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81b833c1)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b9dfb5)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba24fc)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba3a9f)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba518d)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba60ed)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81ba9481)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb541e)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7d70)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
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
In kernel/taskstats.c (ffffffff811a8ca2)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In fs/quota/netlink.c (ffffffff813ce022)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff816985d5)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81942c9a)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff819ddc69)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff819fadca)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81a06b23)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81a28025)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a35e8b)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81a42fec)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffffffff81a6cf2b)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81a6f40a)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81a7981e)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81a7d276)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a7fd48)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81a811f0)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/route.c (ffffffff81a86668)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac3288)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81ad622c)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8477)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81af6efe)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b00b5d)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b317fc)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b591)
Location: include/net/netlink.h:965
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b41068)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81b5045f)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81b6faa3)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81b7203a)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81b8d0b5)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b915dc)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b92bbe)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b942d3)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b95263)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81b9860a)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba441e)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbb9d2)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
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
In kernel/taskstats.c (ffffffff811d27ee)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In fs/quota/netlink.c (ffffffff8141f352)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8170e355)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191aa59)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e7769)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81a8defa)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81aaca0a)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81ab8f71)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81adcdc5)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81aeba7d)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81af945c)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffffffff81b265ab)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81b281aa)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81b33ba7)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81b37456)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81b39b18)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81b3af40)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/route.c (ffffffff81b40da8)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b811e3)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81b94f5c)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8446)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81bb6874)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81bc1f1f)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81bf789c)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81c01db1)
Location: include/net/netlink.h:965
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c08d38)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81c1770f)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81c37bf3)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff81c393ef)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c4ea)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81c5946c)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5dd7c)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f35e)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60a73)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61a93)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81c65167)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c71fae)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b612)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
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
In kernel/taskstats.c (ffffffff8120708c)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In fs/quota/netlink.c (ffffffff81497196)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8183cd26)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fead)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d01d)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81c03b8b)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81c259b5)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81c321ca)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81c5e35d)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81c6e3af)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81c7c365)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffffffff81caf12c)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81cb119a)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81cbf2c8)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81cc2e4e)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81cc5978)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81cc6ee0)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/route.c (ffffffff81ccd918)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1156c)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81d26bda)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3adb2)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81d4a4c8)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81d56264)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81d90d46)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81d9bd1c)
Location: include/net/netlink.h:965
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da3864)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81db34d6)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81dd57ac)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff81dd6ca2)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81dda8bc)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81dfac05)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00057)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e0172c)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e02f75)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e04095)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81e07d81)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15b2f)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32bc2)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
```
In net/mctp/device.c (ffffffff81e37fc9)
Location: include/net/netlink.h:965
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff81e39311)
Location: include/net/netlink.h:965
Inline: True
```
```
In net/mctp/neigh.c (ffffffff81e3b4a0)
Location: include/net/netlink.h:965
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
In kernel/taskstats.c (ffffffff8124f3fc)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In fs/quota/netlink.c (ffffffff8152b1f1)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81972776)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02d3d)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4d1d)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81db323b)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81dd7bf5)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81de559a)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff81e14b54)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e26038)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81e40c35)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_selftests_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffffffff81e6c7f1)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81e6f174)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81e7de68)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81e8213e)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81e84f08)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81e86530)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/route.c (ffffffff81e8d9c4)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed731c)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81eee57a)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f03722)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81f13b68)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81f202c4)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81f5f466)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81f6a9b3)
Location: include/net/netlink.h:1014
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f72ca4)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81f82e36)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff81fa6f3c)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff81fa8642)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81fac5dc)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/wireless/wext-core.c (ffffffff81fcf42f)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd4e77)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd658c)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd7eb5)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd9055)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81fdd2d1)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fecadf)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff8200b622)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
```
In net/mctp/device.c (ffffffff820111f9)
Location: include/net/netlink.h:1014
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff820125d1)
Location: include/net/netlink.h:1014
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82014b60)
Location: include/net/netlink.h:1014
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
In kernel/taskstats.c (ffffffff812667ac)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In fs/quota/netlink.c (ffffffff81563581)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff819b8e46)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c683ed)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d2ed)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/net_namespace.c (ffffffff81e2380b)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81e48a05)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81e56fb6)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/netdev-genl.c (ffffffff81e7ce93)
Location: include/net/netlink.h:1015
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e88464)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e9b5d8)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/netlink/af_netlink.c (ffffffff81ec8851)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81ecb284)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81eda428)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81ede79e)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81ee1838)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81ee2f12)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/route.c (ffffffff81eec0f6)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f363b2)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81f4df38)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63102)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81f73838)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81f7fdc4)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81fbf194)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81fca9e6)
Location: include/net/netlink.h:1015
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd2d9a)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81fe3136)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff8200779c)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff82008fd2)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff8200cd7c)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/devlink/leftover.c (ffffffff820377f9)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_dpipe_entry_ctx_close
  - net/devlink/leftover.c:devlink_nl_port_fill
```
```
In net/devlink/dev.c (ffffffff820459e5)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_fill
```
```
In net/devlink/health.c (ffffffff8204845a)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/wireless/wext-core.c (ffffffff8204b0ab)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82050b17)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8205224c)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053ba5)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054d25)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff820593a1)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068d7f)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff82087ab2)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
```
In net/mctp/device.c (ffffffff8208dfb9)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff8208f3c1)
Location: include/net/netlink.h:1015
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82091980)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
```
In net/handshake/netlink.c (ffffffff82092531)
Location: include/net/netlink.h:1015
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff82094010)
Location: include/net/netlink.h:1015
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
In kernel/taskstats.c (ffffffff8128069c)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
```
```
In fs/quota/netlink.c (ffffffff81599c71)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81a03476)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/regulator/event.c (ffffffff81ae2613)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - drivers/regulator/event.c:reg_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03ddd)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebb8eb)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
```
```
In net/core/net_namespace.c (ffffffff81ee176b)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81f075c5)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81f16316)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/netdev-genl.c (ffffffff81f3d214)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
  - net/core/netdev-genl.c:netdev_nl_napi_fill_one
  - net/core/netdev-genl.c:netdev_nl_dev_fill
```
```
In net/core/page_pool_user.c (ffffffff81f45330)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
```
```
In net/core/fib_rules.c (ffffffff81f4a474)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81f5dd48)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/netlink/af_netlink.c (ffffffff81f8bb51)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81f8e774)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ethtool/netlink.c (ffffffff81f9e205)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/features.c (ffffffff81fa25ce)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81fa56c8)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
```
```
In net/ethtool/tunnels.c (ffffffff81fa6d76)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ipv4/route.c (ffffffff81fb0146)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffc652)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff82014068)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff820296d2)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff8203a028)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff82046444)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8208c62c)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff82098186)
Location: include/net/netlink.h:1036
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a06aa)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff820b1056)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
```
```
In net/ipv6/seg6.c (ffffffff820d662c)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff820d7f42)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff820dbd4c)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
```
```
In net/devlink/dev.c (ffffffff82105328)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_fill
```
```
In net/devlink/port.c (ffffffff82106994)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_fill
```
```
In net/devlink/sb.c (ffffffff8210892b)
Location: include/net/netlink.h:1036
Inline: True
```
```
In net/devlink/dpipe.c (ffffffff8210a4ac)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_dpipe_entry_ctx_close
```
```
In net/devlink/resource.c (ffffffff8210c8ca)
Location: include/net/netlink.h:1036
Inline: True
```
```
In net/devlink/param.c (ffffffff8210e0e6)
Location: include/net/netlink.h:1036
Inline: True
```
```
In net/devlink/region.c (ffffffff821114f7)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_notify_build
```
```
In net/devlink/health.c (ffffffff8211455f)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/devlink/trap.c (ffffffff82114c29)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
```
In net/devlink/rate.c (ffffffff8211898f)
Location: include/net/netlink.h:1036
Inline: True
```
```
In net/devlink/linecard.c (ffffffff82119ace)
Location: include/net/netlink.h:1036
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8211d52b)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff821231c7)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82124a39)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126385)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82127605)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff8212bf21)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213bfff)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff8215d30a)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_dumpit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
```
```
In net/mctp/device.c (ffffffff82164479)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff821658a1)
Location: include/net/netlink.h:1036
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82167f20)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
```
In net/handshake/netlink.c (ffffffff82168e11)
Location: include/net/netlink.h:1036
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff8216a930)
Location: include/net/netlink.h:1036
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
In kernel/taskstats.c (ffff80001020db8c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffff800010437688)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffff800010778d2c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffff800010ad391c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffff800010bbfd28)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffff800010be3fc0)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffff800010bf1918)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffff800010c12f84)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/core/drop_monitor.c (ffff800010c1ca2c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffff800010c2c13c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffff800010c4fc10)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffff800010c51cdc)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffff800010c5753c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92128)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffff800010ca5730)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9030)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffff800010cc3884)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffff800010cca258)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffff800010d027dc)
Location: include/net/netlink.h:900
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
In net/ipv6/addrlabel.c (ffff800010d0b4bc)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/ipv6/route.c (ffff800010d0dc14)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffff800010d22b44)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffff800010d416f8)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffff800010d423a4)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffff800010d60e3c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d66600)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d67a14)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d6975c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6a8a4)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffff800010d6f3a8)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d9fc)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (c044c578)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (c05ff2ec)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/thermal/thermal_core.c (c0bb44dc)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (c0cdb808)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (c0cfe44c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (c0d0a13c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (c0d2a914)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (c0d34974)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (c0d42730)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (c0d5fdec)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (c0d613b8)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (c0d67160)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (c0da0e3c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (c0db20a0)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (c0dc47a0)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (c0dcf060)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (c0dd6224)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (c0e085e8)
Location: include/net/netlink.h:900
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
In net/ipv6/addrlabel.c (c0e114a0)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/ipv6/route.c (c0e14500)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (c0e270f4)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (c0e440fc)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (c0e44ccc)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c0e605c4)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (c0e64e30)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_protocols_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (c0e66588)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67d44)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c0e68e24)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (c0e6d014)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (c0e78558)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (c00000000028bc34)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (c000000000549ac8)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/thermal/thermal_core.c (c000000000bb8c20)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (c000000000c9915c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (c000000000cc7394)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (c000000000cd6500)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (c000000000cfff78)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/core/drop_monitor.c (c000000000d0da30)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (c000000000d22c64)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (c000000000d4e720)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (c000000000d507dc)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (c000000000d58a98)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (c000000000da290c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (c000000000db9610)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (c000000000dd1c54)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (c000000000ddf4f8)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (c000000000de975c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (c000000000e2a098)
Location: include/net/netlink.h:900
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
In net/ipv6/addrlabel.c (c000000000e35b54)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/ipv6/route.c (c000000000e39a84)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (c000000000e52824)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (c000000000e75f84)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (c000000000e77188)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c000000000e9c228)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea27a0)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea4314)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea65bc)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7c3c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (c000000000eae230)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebd550)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffe00016ea98)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffe0002d18bc)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/thermal/thermal_core.c (ffffffe0006cff1e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffe00074d5e0)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffe00076a978)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffe000773640)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffe00078e944)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/core/drop_monitor.c (ffffffe00079691c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffe0007a3740)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffffffe0007bb7b2)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffe0007bcda0)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffe0007c17d2)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f20d0)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffe000800ff2)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffe00080fde8)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffe000818ae6)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffe00081f6e6)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffe00084abce)
Location: include/net/netlink.h:900
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
In net/ipv6/addrlabel.c (ffffffe000852720)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/ipv6/route.c (ffffffe00085589c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffe00086463e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffe00087cdcc)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffe00087da2c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffe000895f6a)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a0de)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b020)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089c690)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d440)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffe0008a0f3e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab218)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff8118df30)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff81366212)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815dc9d8)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8182c990)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff818c43b9)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff818e40f0)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818efc5f)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8190c6e1)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81916536)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff8192397e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffffffff8194140f)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81942896)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff81947ace)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197eda4)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff8198f664)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff819a07c9)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff819aa124)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff819b157c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff819de987)
Location: include/net/netlink.h:900
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
In net/ipv6/addrlabel.c (ffffffff819e7871)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ea22c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff819fcf8b)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a17803)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a1829e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a32694)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a363bc)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a376da)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a3905d)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a03d)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a3dd63)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a490ce)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff81181040)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff81356eb2)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815c8018)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/vxlan.c (ffffffff8176ceee)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In drivers/thermal/thermal_core.c (ffffffff817f4020)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff8187e2f9)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff8189df30)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff818a9a9f)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818c64a1)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff818d02e6)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff818dd72e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffffffff818faeff)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff818fc386)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819015be)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938864)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81949124)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a289)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81963be4)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff8196dbac)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8199b747)
Location: include/net/netlink.h:900
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
In net/ipv6/addrlabel.c (ffffffff819a4631)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a6fec)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff819b9d4b)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff819d45c3)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff819d505e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819ef884)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f2fdc)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f42fa)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f5c7d)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6c5d)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819fa953)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05cbe)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff8118bd00)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff81363ce2)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815e1b68)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8187bfc0)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff819153b9)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81935120)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff81940c8f)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8195d711)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81967566)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81974b0e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffffffff8199259f)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81993a26)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ae79b)
Location: include/net/netlink.h:900
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
In net/ipv4/route.c (ffffffff819b229e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9574)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff819f9f04)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0b069)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81a149c4)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a1be1c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a49407)
Location: include/net/netlink.h:900
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
In net/ipv6/addrlabel.c (ffffffff81a522f1)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a54cac)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a67a0b)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a82283)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a82d1e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a9e244)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa226c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa358a)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa4f0d)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa5eed)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81aa9c13)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4f7e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
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
In kernel/taskstats.c (ffffffff8119967d)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:send_reply
```
```
In fs/quota/netlink.c (ffffffff81377392)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815fba28)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff818979f0)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/net_namespace.c (ffffffff81936599)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/neighbour.c (ffffffff81956830)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
```
```
In net/core/rtnetlink.c (ffffffff8196259f)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8197f961)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff819897f6)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81996ffe)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/netlink/af_netlink.c (ffffffff819b508f)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff819b6516)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff819bb95e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f32e4)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/devinet.c (ffffffff81a04214)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a15849)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/nexthop.c (ffffffff81a1f3d4)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a26d4a)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a55327)
Location: include/net/netlink.h:900
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
In net/ipv6/addrlabel.c (ffffffff81a5e2e1)
Location: include/net/netlink.h:900
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a60c9c)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a73ffa)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/seg6.c (ffffffff81a8eb93)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f5ee)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81aaa444)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae5dc)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aaf9aa)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab128d)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab228d)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81ab5f83)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac131e)
Location: include/net/netlink.h:900
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
</details>
</li>
</ul>

## Differences
