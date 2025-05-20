# Function: <code>__dev_get_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817135e0)
Location: net/core/dev.c:798
Inline: True
Inline callers:
  - net/core/dev.c:dev_new_index
  - net/core/dev.c:register_netdevice
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_getlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff817135e0-ffffffff81713622: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81787201)
Location: net/core/dev.c:802
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff8177b280-ffffffff8177b2d1: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b47c1)
Location: net/core/dev.c:801
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff817a88e0-ffffffff817a8931: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d340c)
Location: net/core/dev.c:808
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff817c6f30-ffffffff817c6f83: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184d7ff)
Location: net/core/dev.c:811
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81840b00-ffffffff81840b53: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188fdb7)
Location: net/core/dev.c:811
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff8188b130-ffffffff8188b183: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b0720)
Location: net/core/dev.c:813
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff818ac170-ffffffff818ac1d1: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fd470)
Location: net/core/dev.c:809
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff818f7a50-ffffffff818f7a8d: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192fa92)
Location: net/core/dev.c:727
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff819297d0-ffffffff8192980d: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04c38)
Location: net/core/dev.c:925
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_mc_drop
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:init_prb_bdqc
```
**Symbols:**

```
ffffffff819fd720-ffffffff819fd75d: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a05258)
Location: net/core/dev.c:928
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_mc_drop
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:init_prb_bdqc
```
**Symbols:**

```
ffffffff819fd340-ffffffff819fd37d: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ed46b)
Location: net/core/dev.c:976
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff819e3bb0-ffffffff819e3bed: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9e68b)
Location: net/core/dev.c:852
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81a94450-ffffffff81a9448d: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c17339)
Location: net/core/dev.c:799
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
**Symbols:**

```
ffffffff81c0a830-ffffffff81c0a878: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc8339)
Location: net/core/dev.c:799
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/link_watch.c:rfc2863_policy
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
**Symbols:**

```
ffffffff81dba6b0-ffffffff81dba6f8: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e386f9)
Location: net/core/dev.c:811
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_add
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/link_watch.c:rfc2863_policy
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
**Symbols:**

```
ffffffff81e2ae90-ffffffff81e2aed8: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ee8f10)
Location: net/core/dev.c:828
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/tcx.c:tcx_link_attach
  - kernel/bpf/tcx.c:tcx_prog_query
  - kernel/bpf/tcx.c:tcx_prog_detach
  - kernel/bpf/tcx.c:tcx_prog_attach
  - drivers/net/netkit.c:netkit_dev_fetch
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_add
  - net/core/rtnetlink.c:rtnl_mdb_get
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/link_watch.c:rfc2863_policy
  - net/core/netdev-genl.c:netdev_nl_queue_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_napi_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
**Symbols:**

```
ffffffff81ee8f10-ffffffff81ee8f58: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bccf74)
Location: net/core/dev.c:727
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffff800010bc5e18-ffff800010bc5e70: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce89b0)
Location: net/core/dev.c:727
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
c0ce1434-c0ce1488: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caad48)
Location: net/core/dev.c:727
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
c000000000ca0a00-c000000000ca0a54: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000757680)
Location: net/core/dev.c:727
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffe00075256c-ffffffe0007525b8: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cfa92)
Location: net/core/dev.c:727
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff818c97d0-ffffffff818c980d: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81889bb2)
Location: net/core/dev.c:727
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - drivers/net/vxlan.c:__vxlan_dev_create
  - drivers/net/vxlan.c:vxlan_config_validate
  - drivers/net/vxlan.c:vxlan_change_mtu
  - drivers/net/vxlan.c:vxlan_fdb_parse
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/ip_tunnel.c:ip_tunnel_bind_dev
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81883710-ffffffff8188374d: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81920a92)
Location: net/core/dev.c:727
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff8191a7d0-ffffffff8191a80d: __dev_get_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct net_device *__dev_get_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81942822)
Location: net/core/dev.c:727
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_new_index
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/ipv4/route.c:ip_error
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff8193ba90-ffffffff8193bacd: __dev_get_by_index (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
