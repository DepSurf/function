# Function: <code>skb_trim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81705e60)
Location: net/core/skbuff.c:1481
Inline: True
Direct callers:
  - kernel/taskstats.c:mk_reply
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
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
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getcap
```
**Symbols:**

```
ffffffff81705e60-ffffffff81705eac: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176c370)
Location: net/core/skbuff.c:1486
Inline: True
Direct callers:
  - kernel/taskstats.c:mk_reply
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
```
**Symbols:**

```
ffffffff8176c370-ffffffff8176c3bc: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799480)
Location: net/core/skbuff.c:1486
Inline: True
Direct callers:
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
```
**Symbols:**

```
ffffffff81799480-ffffffff817994cc: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b86d0)
Location: net/core/skbuff.c:1499
Inline: True
Direct callers:
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb
```
**Symbols:**

```
ffffffff817b86d0-ffffffff817b870d: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8182fd40)
Location: net/core/skbuff.c:1744
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
**Symbols:**

```
ffffffff8182fd40-ffffffff8182fd7e: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187c270)
Location: net/core/skbuff.c:1746
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff8187c270-ffffffff8187c2ad: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189a800)
Location: net/core/skbuff.c:1756
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff8189a800-ffffffff8189a834: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1915
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff818eeb00-ffffffff818eeb13: skb_trim.cold (STB_LOCAL)
ffffffff818e5470-ffffffff818e54a5: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81918cc0)
Location: net/core/skbuff.c:1915
Inline: True
Direct callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff81918cc0-ffffffff81918cf4: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819e9db0)
Location: net/core/skbuff.c:1914
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:diag_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_terse
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
**Symbols:**

```
ffffffff819e9db0-ffffffff819e9de6: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819e9b50)
Location: net/core/skbuff.c:1925
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:diag_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/pause.c:pause_put_stats
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
**Symbols:**

```
ffffffff819e9b50-ffffffff819e9b86: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819cfc90)
Location: net/core/skbuff.c:1967
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:diag_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/stats.c:stats_put_stats
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
**Symbols:**

```
ffffffff819cfc90-ffffffff819cfcc6: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a7f6c0)
Location: net/core/skbuff.c:2039
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:diag_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/stats.c:stats_put_stats
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
**Symbols:**

```
ffffffff81a7f6c0-ffffffff81a7f6f6: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf3ae0)
Location: net/core/skbuff.c:2088
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/bpf_sk_storage.c:diag_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_fill_reply_header
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mctp/device.c:mctp_fill_addrinfo
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
**Symbols:**

```
ffffffff81bf3ae0-ffffffff81bf3b34: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da17f0)
Location: net/core/skbuff.c:2291
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_selftests_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/bpf_sk_storage.c:diag_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_fill_reply_header
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mctp/device.c:mctp_fill_addrinfo
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
**Symbols:**

```
ffffffff81da17f0-ffffffff81da1844: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e11320)
Location: net/core/skbuff.c:2455
Inline: True
Direct callers:
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/bpf_sk_storage.c:diag_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_fill_reply_header
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
  - net/ethtool/mm.c:mm_fill_reply
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_nl_param_value_fill_one
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_action_put
  - net/devlink/leftover.c:devlink_dpipe_match_put
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mctp/device.c:mctp_fill_addrinfo
  - net/mctp/neigh.c:mctp_rtm_getneigh
  - net/handshake/netlink.c:handshake_genl_notify
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
```
**Symbols:**

```
ffffffff81e11320-ffffffff81e11368: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecde50)
Location: net/core/skbuff.c:2543
Inline: True
Direct callers:
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_parents
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
  - net/core/netdev-genl.c:netdev_nl_napi_fill_one
  - net/core/netdev-genl.c:netdev_nl_dev_fill
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/bpf_sk_storage.c:diag_get
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_fill_reply_header
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
  - net/ethtool/mm.c:mm_fill_reply
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/devlink/netlink.c:devlink_nl_put_nested_handle
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/port.c:devlink_nl_port_fill
  - net/devlink/port.c:devlink_nl_port_function_attrs_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_action_put
  - net/devlink/dpipe.c:devlink_dpipe_match_put
  - net/devlink/param.c:devlink_nl_param_value_fill_one
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_notify_build
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_getapptrust
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_dumpit
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mctp/device.c:mctp_fill_addrinfo
  - net/mctp/neigh.c:mctp_rtm_getneigh
  - net/handshake/netlink.c:handshake_genl_notify
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
```
**Symbols:**

```
ffffffff81ecde50-ffffffff81ecde98: skb_trim (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb08f8)
Location: net/core/skbuff.c:1915
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffff800010bb08f8-ffff800010bb095c: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cce330)
Location: net/core/skbuff.c:1915
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_protocols_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
c0cce330-c0cce38c: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8ad20)
Location: net/core/skbuff.c:1915
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
c000000000c8ad20-c000000000c8ad6c: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000741b46)
Location: net/core/skbuff.c:1915
Inline: False
Direct callers:
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffe000741b46-ffffffe000741b98: skb_trim (STB_GLOBAL)
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
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b8cc0)
Location: net/core/skbuff.c:1915
Inline: True
Direct callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff818b8cc0-ffffffff818b8cf4: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81872c10)
Location: net/core/skbuff.c:1915
Inline: True
Direct callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - drivers/net/vxlan.c:vxlan_fdb_info
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff81872c10-ffffffff81872c44: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81909cc0)
Location: net/core/skbuff.c:1915
Inline: True
Direct callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_stat_cpu_dump
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_expect_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_stat_ct
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_ct_stat_cpu_dump
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff81909cc0-ffffffff81909cf4: skb_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void skb_trim(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192adc0)
Location: net/core/skbuff.c:1915
Inline: True
Direct callers:
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:rtnetlink_ifinfo_prep
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
**Symbols:**

```
ffffffff8192adc0-ffffffff8192adf4: skb_trim (STB_GLOBAL)
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
