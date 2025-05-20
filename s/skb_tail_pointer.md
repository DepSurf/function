# Function: <code>skb_tail_pointer</code>

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
In kernel/audit.c (ffffffff81121e4a)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_n_string
```
```
In kernel/taskstats.c (ffffffff8113e7bb)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - kernel/taskstats.c:mk_reply
```
```
In kernel/bpf/core.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/core/skbuff.c (ffffffff817059b4)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/gen_stats.c (ffffffff8170efae)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/core/neighbour.c (ffffffff817260a1)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8172cfd5)
Location: include/linux/skbuff.h:1766
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
```
```
In net/core/fib_rules.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff8173e2d3)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81743782)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81745c94)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81747264)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump
```
```
In net/sched/ematch.c (ffffffff817495d2)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8174fd56)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817812ac)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff817a855b)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff817cb8c1)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/addrlabel.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817f90a5)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d6f1)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/skbuff.h:1766
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180feee)
Location: include/linux/skbuff.h:1766
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81812bf0)
Location: include/linux/skbuff.h:1766
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
In kernel/audit.c (ffffffff81129eec)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff811473bf)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffffffff81180316)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In fs/quota/netlink.c (ffffffff812a30a6)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff814d85fb)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff816e6e02)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffff81770f65)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/gen_stats.c (ffffffff81776b8a)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (ffffffff8177776a)
Location: include/linux/skbuff.h:1867
Inline: True
```
```
In net/core/dev.c (ffffffff8177dcb1)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81790ef9)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817991a7)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
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
```
```
In net/core/fib_rules.c (ffffffff817a6188)
Location: include/linux/skbuff.h:1867
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff817aac43)
Location: include/linux/skbuff.h:1867
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817b0622)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817b2beb)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff817b4b20)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff817b6604)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff817bc3bd)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff817bfedf)
Location: include/linux/skbuff.h:1867
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cddf9)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff817eec09)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:1867
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff817fbb06)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/devinet.c (ffffffff817fde6b)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:1867
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b564)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff81815f3b)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff818388ca)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff81840065)
Location: include/linux/skbuff.h:1867
Inline: True
```
```
In net/ipv6/route.c (ffffffff818423da)
Location: include/linux/skbuff.h:1867
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff8184f2f7)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:1867
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81855b7c)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:1867
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81863e2e)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff81868b8d)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:1867
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:1867
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8187b8f4)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187f870)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880c67)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8188249d)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8188349d)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81886da0)
Location: include/linux/skbuff.h:1867
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/switchdev/switchdev.c (ffffffff8188ae27)
Location: include/linux/skbuff.h:1867
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
In kernel/audit.c (ffffffff81133c0c)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff8115125f)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffffffff8118c186)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In fs/quota/netlink.c (ffffffff812b8a86)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff814face3)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81716252)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffff8179e085)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/gen_stats.c (ffffffff817a3efa)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (ffffffff817a47ea)
Location: include/linux/skbuff.h:1882
Inline: True
```
```
In net/core/dev.c (ffffffff817ab621)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff817be73c)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817c6f57)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff817d4ce8)
Location: include/linux/skbuff.h:1882
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff817d99e3)
Location: include/linux/skbuff.h:1882
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817da1fb)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_lwt_prog
  - net/core/lwt_bpf.c:bpf_fill_lwt_prog
```
```
In net/sched/sch_api.c (ffffffff817dfd62)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817e246a)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff817e43e0)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff817e6094)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/genetlink.c (ffffffff817ebccd)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/ipv4/route.c (ffffffff817f308b)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdb59)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f619)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:1882
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8182ca56)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/devinet.c (ffffffff8182edcb)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:1882
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c67d)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff818476eb)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/addrconf.c (ffffffff8186a3fa)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff81871ce5)
Location: include/linux/skbuff.h:1882
Inline: True
```
```
In net/ipv6/route.c (ffffffff81874132)
Location: include/linux/skbuff.h:1882
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff8188124d)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:1882
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff8188793c)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:1882
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff818964de)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81899913)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff8189b9dd)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:1882
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:1882
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff818b01b4)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b4120)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b5517)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6d4d)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7d3d)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff818bb610)
Location: include/linux/skbuff.h:1882
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/switchdev/switchdev.c (ffffffff818bf1f7)
Location: include/linux/skbuff.h:1882
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
In kernel/audit.c (ffffffff811350dc)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff811538dc)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffffffff8118fe0d)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
```
```
In fs/quota/netlink.c (ffffffff812c5e52)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8150a21d)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8172e052)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffff817bbe31)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/gen_stats.c (ffffffff817c204a)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/net_namespace.c (ffffffff817c292a)
Location: include/linux/skbuff.h:1875
Inline: True
```
```
In net/core/dev.c (ffffffff817c9c91)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff817dd7e7)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff817e584e)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff817f4033)
Location: include/linux/skbuff.h:1875
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff817f8c15)
Location: include/linux/skbuff.h:1875
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff817f9400)
Location: include/linux/skbuff.h:1875
Inline: True
```
```
In net/sched/sch_api.c (ffffffff817ff3bf)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81801d47)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81803e68)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff81805b2f)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff8180a41f)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8180bc2d)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:1875
Inline: True
```
```
In net/ipv4/route.c (ffffffff81813a2e)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181df96)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff81840323)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:1875
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8184deb6)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/devinet.c (ffffffff8184f2c5)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:1875
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8185ddc7)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff8186a9ae)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8188e953)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81896a65)
Location: include/linux/skbuff.h:1875
Inline: True
```
```
In net/ipv6/route.c (ffffffff81898dde)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_add_nexthop
```
```
In net/ipv6/ndisc.c (ffffffff818a72ef)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff818adf35)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:1875
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff818bca64)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff818bfb23)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff818c1da3)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:1875
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:1875
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff818d6b72)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818daad0)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dbe6b)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd62c)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de62c)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff818e1fe3)
Location: include/linux/skbuff.h:1875
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/switchdev/switchdev.c (ffffffff818e5b2d)
Location: include/linux/skbuff.h:1875
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
In kernel/audit.c (ffffffff81141e2c)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff811600dc)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffffffff8119d082)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:1962
Inline: True
```
```
In fs/quota/netlink.c (ffffffff812e9d02)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8154c71d)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8179f682)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffff81835ff1)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/gen_stats.c (ffffffff8183ba4a)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/net_namespace.c (ffffffff8183c26a)
Location: include/linux/skbuff.h:1962
Inline: True
```
```
In net/core/dev.c (ffffffff81843591)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81857b67)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818608ee)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/fib_rules.c (ffffffff8186f798)
Location: include/linux/skbuff.h:1962
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff818764f5)
Location: include/linux/skbuff.h:1962
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81876d10)
Location: include/linux/skbuff.h:1962
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8187d12f)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8187fdb7)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff818824a4)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff81884852)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff8188944c)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff8188abbd)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:1962
Inline: True
```
```
In net/ipv4/route.c (ffffffff81893091)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189cea6)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf6c3)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:1962
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff818cdbd6)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/devinet.c (ffffffff818ceef5)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:1962
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff818dddf7)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff818eb13c)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8190ffa3)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81917ed4)
Location: include/linux/skbuff.h:1962
Inline: True
```
```
In net/ipv6/route.c (ffffffff8191a0e4)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_add_nexthop
```
```
In net/ipv6/ndisc.c (ffffffff81929d51)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff81930bb5)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:1962
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff8193fb84)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81942bf3)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff819456e3)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:1962
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:1962
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8195c742)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819606b0)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961a4b)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8196321c)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8196422c)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81967d85)
Location: include/linux/skbuff.h:1962
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In kernel/audit.c (ffffffff811507ec)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff8116f01c)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffffffff811b17b2)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:1973
Inline: True
```
```
In fs/quota/netlink.c (ffffffff81316c06)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81582e5d)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff817e6c62)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffff81880114)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/gen_stats.c (ffffffff818861ca)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/net_namespace.c (ffffffff81886cca)
Location: include/linux/skbuff.h:1973
Inline: True
```
```
In net/core/dev.c (ffffffff8188da71)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff818a2ca9)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818aa7be)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/filter.c (ffffffff818b1036)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/fib_rules.c (ffffffff818c0fd4)
Location: include/linux/skbuff.h:1973
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff818c7c1f)
Location: include/linux/skbuff.h:1973
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818c8165)
Location: include/linux/skbuff.h:1973
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818cf780)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d4f7b)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff818d5f15)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff818d83cf)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff818dce29)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netlink/genetlink.c (ffffffff818de1ec)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:1973
Inline: True
```
```
In net/ipv4/route.c (ffffffff818e7178)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f138b)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff819152ae)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:1973
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:1973
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81924373)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/devinet.c (ffffffff81925cb8)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:1973
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81934972)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff8194190d)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81944464)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff819673b3)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8196f594)
Location: include/linux/skbuff.h:1973
Inline: True
```
```
In net/ipv6/route.c (ffffffff81972220)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_add_nexthop
```
```
In net/ipv6/ndisc.c (ffffffff81981d80)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff819897f1)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8198c780)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffffffff819989ca)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff8199bb2a)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff8199d1d2)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff819a861f)
Location: include/linux/skbuff.h:1973
Inline: True
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:1973
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:1973
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff819b5f22)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819b9e70)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb1bb)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bca6c)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bdacc)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819c15be)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cb095)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/audit.c (ffffffff8115d489)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff8117cb1c)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffffffff811bfe42)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:2051
Inline: True
```
```
In fs/quota/netlink.c (ffffffff8132dbb6)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8159af8d)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81813012)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffff818a1014)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/gen_stats.c (ffffffff818a694a)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/net_namespace.c (ffffffff818a73c9)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff818ae911)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff818c5a8e)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818d065b)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
```
```
In net/core/filter.c (ffffffff818d5aa9)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/fib_rules.c (ffffffff818e9de1)
Location: include/linux/skbuff.h:2051
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff818f0d7f)
Location: include/linux/skbuff.h:2051
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818f12d5)
Location: include/linux/skbuff.h:2051
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818fab20)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818fdea7)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81902719)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff81904bbf)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff819097ff)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8190abac)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2051
Inline: True
```
```
In net/ipv4/route.c (ffffffff81914056)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191eee8)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff819438ce)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2051
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2051
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81952f42)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff81954c54)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:2051
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819642bf)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
```
```
In net/ipv4/ipmr.c (ffffffff819711be)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81974704)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8199c9c0)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a5121)
Location: include/linux/skbuff.h:2051
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a7978)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_add_nexthop
```
```
In net/ipv6/ndisc.c (ffffffff819b8429)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff819c0102)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c2ffd)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffffffff819cf327)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff819d26fa)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff819d3d2f)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff819df16f)
Location: include/linux/skbuff.h:2051
Inline: True
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:2051
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:2051
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff819ed1e2)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1140)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f242b)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3cbc)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4c6c)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819f8b11)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a042a8)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/audit.c (ffffffff81169bc7)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff811899cd)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffffffff811d0672)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:2139
Inline: True
```
```
In fs/quota/netlink.c (ffffffff813558f2)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815cc608)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff818550b0)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffff818eba07)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff818f1dba)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/net_namespace.c (ffffffff818f2469)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff818fa204)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81911ab0)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8191d4f1)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/filter.c (ffffffff8192324c)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/fib_rules.c (ffffffff81939844)
Location: include/linux/skbuff.h:2139
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff8194271d)
Location: include/linux/skbuff.h:2139
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81942f75)
Location: include/linux/skbuff.h:2139
Inline: True
```
```
In net/core/devlink.c (ffffffff81951ac7)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff8195a3cc)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8195d815)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8196397c)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff81965e12)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff8196ab49)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8196bf9c)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2139
Inline: True
```
```
In net/ipv4/route.c (ffffffff81971240)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981829)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7ea1)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2139
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2139
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819b79e5)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff819b8bc4)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:2139
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819c9e69)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/nexthop.c (ffffffff819d3814)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff819da93e)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff819de244)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a08b96)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a115c1)
Location: include/linux/skbuff.h:2139
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a13fd1)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a26e97)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff81a2ef48)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a31e43)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffffffff81a3e076)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81a414f3)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a41fae)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff81a4dcdf)
Location: include/linux/skbuff.h:2139
Inline: True
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:2139
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:2139
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81a5c3d7)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a603fc)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a6177a)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a6311b)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a6412b)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a68073)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a7354e)
Location: include/linux/skbuff.h:2139
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/audit.c (ffffffff81175a67)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff81195910)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffffffff811dcc02)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In fs/quota/netlink.c (ffffffff8136dc32)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815ed888)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81886b10)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffff8191db66)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff81923d0a)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/net_namespace.c (ffffffff819243b9)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff8192c344)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81944120)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff8194fb41)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/filter.c (ffffffff8195547c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/fib_rules.c (ffffffff8196c711)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81976433)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffff81977645)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81977f25)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/devlink.c (ffffffff81983a9d)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff8199086c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81993dd5)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8199a4fc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff8199c8a2)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff819a159f)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff819a294c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/route.c (ffffffff819a7c5e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b8069)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff819def34)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819ee6e5)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff819ef8c4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00a29)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/nexthop.c (ffffffff81a0a384)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a11829)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81a152e4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a3f2a6)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a481e1)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4abc1)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a5d8fb)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff81a65a98)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a68993)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffffffff81a74ce6)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81a78173)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a78c0e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff81a848af)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81a93004)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a9702c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a9834a)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a99ccd)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9acad)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a9e9d3)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa9d3e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/audit.c (ffffffff811881c7)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff811aa96f)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_cpu_listeners
```
```
In kernel/bpf/core.c (ffffffff811f9622)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (ffffffff81227d79)
Location: include/linux/skbuff.h:2176
Inline: True
```
```
In fs/quota/netlink.c (ffffffff813b5762)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81699408)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffff819f0908)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff819f773a)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (ffffffff819f8089)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff819ff854)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81a14192)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a2135f)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
```
```
In net/core/filter.c (ffffffff81a28281)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/fib_rules.c (ffffffff81a405c5)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a4b2ff)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffff81a4c411)
Location: include/linux/skbuff.h:2176
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a4c695)
Location: include/linux/skbuff.h:2176
Inline: True
```
```
In net/core/devlink.c (ffffffff81a5f705)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61817)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a689ac)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a7187f)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a7345a)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_terse
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_dump_walker
```
```
In net/sched/ematch.c (ffffffff81a75a1f)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff81a7af72)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81a7c76a)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81a7d9ae)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2176
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81a867f7)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/bitset.c (ffffffff81a8745f)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a87fcb)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/features.c (ffffffff81a89f86)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a8d191)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/route.c (ffffffff81a913c7)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa298b)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc520)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (ffffffff81aceae0)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8c91)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/icmp.c (ffffffff81adca15)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff81addd0c)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81ae56a6)
Location: include/linux/skbuff.h:2176
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81aefcb0)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_multipath
  - net/ipv4/fib_semantics.c:fib_add_multipath
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af87d2)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
```
```
In net/ipv4/nexthop.c (ffffffff81afaee7)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b04a8d)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/ipv4/ipmr_base.c (ffffffff81b062d4)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b34f26)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f081)
Location: include/linux/skbuff.h:2176
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b45128)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81b547f6)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
```
In net/ipv6/icmp.c (ffffffff81b5e3d9)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b60e3d)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffffffff81b6ef36)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81b72152)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81b74651)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f89e)
Location: include/linux/skbuff.h:2176
Inline: True
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b81c9b)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b826fa)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81b82855)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/wireless/wext-core.c (ffffffff81b8e315)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b928ac)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93e37)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9551d)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b9647d)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81b997c1)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5f3e)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bb2a43)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb368b)
Location: include/linux/skbuff.h:2176
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In kernel/audit.c (ffffffff81185557)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff811a7f1f)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_cpu_listeners
```
```
In kernel/bpf/core.c (ffffffff811f8662)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (ffffffff8122ead9)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
```
```
In fs/quota/netlink.c (ffffffff813c6f92)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff816b6525)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f73a)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/skbuff.c (ffffffff819f0778)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff819f71aa)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (ffffffff819f7ae9)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff819ff5b4)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81a1443a)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a1f8eb)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_fill_link_af
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_vf_ports_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
  - net/core/rtnetlink.c:rtnl_link_slave_info_fill
```
```
In net/core/filter.c (ffffffff81a28a91)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/fib_rules.c (ffffffff81a432c5)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a50f2f)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_hw_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_stats_put
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:net_dm_hw_entries_put
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffff81a52091)
Location: include/linux/skbuff.h:2197
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a52315)
Location: include/linux/skbuff.h:2197
Inline: True
```
```
In net/core/devlink.c (ffffffff81a67ef5)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_trap_policer_stats_put
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_trap_metadata_put
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_fields_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6a0f7)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a710bc)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a7a2ff)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a7c05a)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/sched/ematch.c (ffffffff81a7e7cf)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff81a83d6c)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81a85a52)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81a873ed)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2197
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81a90107)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/bitset.c (ffffffff81a90de4)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a9197b)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/features.c (ffffffff81a93856)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/pause.c (ffffffff81a9556d)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_put_stats
  - net/ethtool/pause.c:pause_put_stats
```
```
In net/ethtool/cabletest.c (ffffffff81a968d1)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81a97790)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ipv4/route.c (ffffffff81a9b248)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacc9b)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad84ed)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (ffffffff81adab00)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ae51a1)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/icmp.c (ffffffff81ae9754)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff81aeaaec)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81af2566)
Location: include/linux/skbuff.h:2197
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81afcbf0)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_multipath
  - net/ipv4/fib_semantics.c:fib_add_multipath
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05622)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
```
```
In net/ipv4/nexthop.c (ffffffff81b085b7)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81b12bfd)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/ipv4/ipmr_base.c (ffffffff81b144c4)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b43b4b)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b4db01)
Location: include/linux/skbuff.h:2197
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b53acb)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81b62e16)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
```
In net/ipv6/icmp.c (ffffffff81b6cbb0)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b6f5ad)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffffffff81b7da66)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81b80eb2)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81b833c1)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
```
In net/ipv6/seg6_local.c (ffffffff81b8e94e)
Location: include/linux/skbuff.h:2197
Inline: True
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b9138b)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b91d79)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81b91eb5)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/wireless/wext-core.c (ffffffff81b9dfb5)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba24fc)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba3a9f)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba518d)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba60ed)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81ba9481)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb541e)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bc6e73)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7d70)
Location: include/linux/skbuff.h:2197
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In kernel/audit.c (ffffffff81186557)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff811a8ca2)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In kernel/bpf/core.c (ffffffff811f9455)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In fs/quota/netlink.c (ffffffff813ce022)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff816985d5)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81942c9a)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/skbuff.c (ffffffff819d5e88)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff819dd33a)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (ffffffff819ddc69)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff819e5d24)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff819fadca)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81a069b3)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/filter.c (ffffffff81a0fe92)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/xdp.c (ffffffff81a1f94e)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/fib_rules.c (ffffffff81a28025)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a35d59)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffff81a379b6)
Location: include/linux/skbuff.h:2213
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a37af5)
Location: include/linux/skbuff.h:2213
Inline: True
```
```
In net/core/devlink.c (ffffffff81a42f84)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81a5273c)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81a5988c)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a5f12f)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81a64c87)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/sched/ematch.c (ffffffff81a6762f)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff81a6cf2b)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81a6f3f6)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81a704bd)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2213
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81a7981e)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/bitset.c (ffffffff81a7a5e1)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81a7b3ac)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/features.c (ffffffff81a7d276)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/pause.c (ffffffff81a7f0ec)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a803a1)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81a811f0)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81a81532)
Location: include/linux/skbuff.h:2213
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81a8217b)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_stats
```
```
In net/ipv4/route.c (ffffffff81a86668)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a97eeb)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac3288)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac5b39)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ad039f)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/icmp.c (ffffffff81ad4e14)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff81ad622c)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81addd46)
Location: include/linux/skbuff.h:2213
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae82ca)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af0ea2)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
```
```
In net/ipv4/nexthop.c (ffffffff81af6efe)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81b0095b)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81b022c4)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81b317ab)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b591)
Location: include/linux/skbuff.h:2213
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b4108d)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81b51134)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
```
In net/ipv6/icmp.c (ffffffff81b5af17)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b5d9a3)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffffffff81b6c656)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81b6faa3)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81b7203a)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d2f4)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b8058a)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b80fcd)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81b81105)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/wireless/wext-core.c (ffffffff81b8d0b5)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b915dc)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b92bbe)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b942d3)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b95263)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81b9860a)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba441e)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81bb7ba3)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbb9d2)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In kernel/audit.c (ffffffff811ae947)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff811d27ee)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In kernel/bpf/core.c (ffffffff8122aae5)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In fs/quota/netlink.c (ffffffff8141f352)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8170e355)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191a985)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e7769)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/skbuff.c (ffffffff81a82f66)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff81a8d5ca)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (ffffffff81a8defa)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff81a97f04)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81aaca0a)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81ab8e01)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/filter.c (ffffffff81ac2162)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/xdp.c (ffffffff81ad390e)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/fib_rules.c (ffffffff81adcdc5)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81aeb93a)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffff81aed7d6)
Location: include/linux/skbuff.h:2242
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81aed945)
Location: include/linux/skbuff.h:2242
Inline: True
```
```
In net/core/devlink.c (ffffffff81af93f4)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b1ac)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81b1294c)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b17fef)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81b1df57)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/sched/ematch.c (ffffffff81b20b0f)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff81b265ab)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81b28196)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81b29c0d)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2242
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81b33ba7)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
```
In net/ethtool/bitset.c (ffffffff81b349f1)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81b357bc)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/features.c (ffffffff81b37456)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/pause.c (ffffffff81b3914c)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81b3a171)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81b3af40)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81b3b2b2)
Location: include/linux/skbuff.h:2242
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81b3bd3b)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_stats
```
```
In net/ipv4/route.c (ffffffff81b40da8)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b5337b)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b811e3)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84374)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81b8edbd)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/icmp.c (ffffffff81b93cc4)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff81b94f5c)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81b9d1e6)
Location: include/linux/skbuff.h:2242
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8331)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1382)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
```
```
In net/ipv4/nexthop.c (ffffffff81bb6874)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81bc1e3a)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc4178)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff81bdfef5)
Location: include/linux/skbuff.h:2242
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81bf784b)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81c01db1)
Location: include/linux/skbuff.h:2242
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c08d5d)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81c18594)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
```
In net/ipv6/icmp.c (ffffffff81c22627)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81c24e23)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/datagram.c (ffffffff81c3452a)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81c37bf3)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff81c393ef)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c4ea)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_local.c (ffffffff81c484a4)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/ipv6/exthdrs_core.c (ffffffff81c4c5aa)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_icmp.c (ffffffff81c4cfed)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81c4d125)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/wireless/wext-core.c (ffffffff81c5946c)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5dd7c)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f35e)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60a73)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61a93)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81c65167)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c71fae)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81c870f3)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b612)
Location: include/linux/skbuff.h:2242
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In kernel/audit.c (ffffffff811e0907)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff8120708c)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In kernel/bpf/core.c (ffffffff8126c3e5)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In fs/quota/netlink.c (ffffffff81497196)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff8183cd26)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fddc)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d01d)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/skbuff.c (ffffffff81bf7a24)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff81c02fca)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (ffffffff81c03b8b)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff81c13b66)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81c259b5)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81c33012)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
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
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/filter.c (ffffffff81c3c5f2)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/xdp.c (ffffffff81c512cc)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/gro.c (ffffffff81c538c4)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/fib_rules.c (ffffffff81c5e35d)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81c6e276)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffff81c700e6)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/lwt_bpf.c (ffffffff81c70805)
Location: include/linux/skbuff.h:2593
Inline: True
```
```
In net/core/devlink.c (ffffffff81c7c300)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91725)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81c9aef1)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81ca2585)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81ca592f)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/sched/ematch.c (ffffffff81ca94c1)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff81caf12c)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81cb1182)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81cb2e2d)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2593
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81cbf2c8)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_fill_reply_header
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81cbffa0)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81cc118c)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/features.c (ffffffff81cc2e4e)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/pause.c (ffffffff81cc4f4e)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81cc6061)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81cc6ee0)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81cc71e2)
Location: include/linux/skbuff.h:2593
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81cc7f8c)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
  - net/ethtool/stats.c:stat_put
```
```
In net/ipv4/route.c (ffffffff81ccd918)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdfa6f)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1156c)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (ffffffff81d14b33)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81d1fa92)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/icmp.c (ffffffff81d24bba)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff81d26bda)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81d2f346)
Location: include/linux/skbuff.h:2593
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3ac9d)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44941)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
```
```
In net/ipv4/nexthop.c (ffffffff81d4a4c8)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81d5617f)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/ipv4/ipmr_base.c (ffffffff81d59011)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff81d76f77)
Location: include/linux/skbuff.h:2593
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d90cf8)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81d9bd1c)
Location: include/linux/skbuff.h:2593
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da3ab8)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81db4623)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
```
In net/ipv6/icmp.c (ffffffff81dbf3cf)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81dc2127)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/datagram.c (ffffffff81dd1e28)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81dd57ac)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff81dd6ca2)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81dda8bc)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_local.c (ffffffff81de79d5)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/ipv6/exthdrs_core.c (ffffffff81dec950)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_icmp.c (ffffffff81ded4a4)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81ded5f5)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/wireless/wext-core.c (ffffffff81dfac05)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00057)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e0172c)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e02f75)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e04095)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81e07d81)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15b2f)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff81e2d923)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32bc2)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff81e37fc9)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff81e39296)
Location: include/linux/skbuff.h:2593
Inline: True
```
```
In net/mctp/neigh.c (ffffffff81e3b4a0)
Location: include/linux/skbuff.h:2593
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
In kernel/audit.c (ffffffff812266b7)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff8124f3fc)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In kernel/bpf/core.c (ffffffff812c1405)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In fs/quota/netlink.c (ffffffff8152b1f1)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81972776)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02c6c)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4d1d)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/skbuff.c (ffffffff81da6784)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff81db263a)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (ffffffff81db323b)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff81dc31e6)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81dd7bf5)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81de6432)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
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
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/filter.c (ffffffff81df4162)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/xdp.c (ffffffff81e06a70)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/gro.c (ffffffff81e09074)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/fib_rules.c (ffffffff81e14b54)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e25efc)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffff81e28056)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/lwt_bpf.c (ffffffff81e28805)
Location: include/linux/skbuff.h:2490
Inline: True
```
```
In net/core/devlink.c (ffffffff81e40bd0)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_policer_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_selftests_fill
  - net/core/devlink.c:devlink_nl_selftests_fill
  - net/core/devlink.c:devlink_nl_selftests_fill
  - net/core/devlink.c:devlink_nl_flash_update_fill
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_entry_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4ccc5)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81e57381)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81e5efa5)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81e639cf)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/sched/ematch.c (ffffffff81e66401)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff81e6c7f1)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81e6f15c)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81e70ecd)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2490
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81e7de68)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_fill_reply_header
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81e7ebb0)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81e7fecc)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/features.c (ffffffff81e8213e)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/pause.c (ffffffff81e8444e)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81e85651)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81e86530)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81e86862)
Location: include/linux/skbuff.h:2490
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81e876ac)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
  - net/ethtool/stats.c:stat_put
```
```
In net/ipv4/route.c (ffffffff81e8d9c4)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9fe0f)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed731c)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (ffffffff81edac73)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6c82)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/icmp.c (ffffffff81eec3aa)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff81eee57a)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81ef73f6)
Location: include/linux/skbuff.h:2490
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f0360d)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0da01)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
```
```
In net/ipv4/nexthop.c (ffffffff81f13b68)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81f201df)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/ipv4/ipmr_base.c (ffffffff81f23615)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff81f437e7)
Location: include/linux/skbuff.h:2490
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f5f418)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81f6a9b3)
Location: include/linux/skbuff.h:2490
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f72ef8)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81f841a3)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
```
In net/ipv6/icmp.c (ffffffff81f8fb1f)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81f92817)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/datagram.c (ffffffff81fa3278)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81fa6f3c)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff81fa8642)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff81fac5dc)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_local.c (ffffffff81fbbf3d)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/ipv6/exthdrs_core.c (ffffffff81fc0720)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_icmp.c (ffffffff81fc12c4)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81fc1405)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/wireless/wext-core.c (ffffffff81fcf42f)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd4e77)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd658c)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd7eb5)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd9055)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81fdd2d1)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fecadf)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff82005eb3)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff8200b622)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff820111f9)
Location: include/linux/skbuff.h:2490
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff82012556)
Location: include/linux/skbuff.h:2490
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82014b60)
Location: include/linux/skbuff.h:2490
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
In kernel/audit.c (ffffffff8123cc97)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff812667ac)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In kernel/bpf/core.c (ffffffff812e81d5)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In fs/quota/netlink.c (ffffffff81563581)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff819b8e46)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/virtio_net.c (ffffffff81c555ff)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable_xdp
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c6831c)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d2ed)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/skbuff.c (ffffffff81e15b79)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff81e22c0a)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (ffffffff81e2380b)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff81e32756)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81e48a05)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81e57408)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
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
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/filter.c (ffffffff81e65d72)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/xdp.c (ffffffff81e7838b)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/gro.c (ffffffff81e7b6c6)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/netdev-genl.c (ffffffff81e7ce93)
Location: include/linux/skbuff.h:2533
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e88464)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e9b49c)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffff81e9d692)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/lwt_bpf.c (ffffffff81e9de25)
Location: include/linux/skbuff.h:2533
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea83e5)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81eb33ac)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81eb76b5)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81ebfa60)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/sched/ematch.c (ffffffff81ec2331)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff81ec8851)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81ecb26c)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81eccfed)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2533
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81eda428)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_fill_reply_header
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81edb1a0)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81edc5fc)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/features.c (ffffffff81ede79e)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/pause.c (ffffffff81ee0fe4)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81ee1f81)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81ee2f12)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81ee32b2)
Location: include/linux/skbuff.h:2533
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81ee42fc)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
  - net/ethtool/stats.c:stat_put
```
```
In net/ethtool/mm.c (ffffffff81ee59cd)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ipv4/route.c (ffffffff81eec0f6)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe65f)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f363b2)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (ffffffff81f39d55)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81f46522)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/icmp.c (ffffffff81f4c19a)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff81f4df38)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81f56e76)
Location: include/linux/skbuff.h:2533
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f62fed)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6d6a1)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
```
```
In net/ipv4/nexthop.c (ffffffff81f73838)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff81f7fcdf)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/ipv4/ipmr_base.c (ffffffff81f83165)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa2fc7)
Location: include/linux/skbuff.h:2533
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fbf146)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81fca9e6)
Location: include/linux/skbuff.h:2533
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd2fee)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81fe44b6)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
```
In net/ipv6/icmp.c (ffffffff81ff034f)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81ff3427)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/datagram.c (ffffffff82003b2e)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff8200779c)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff82008fd2)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff8200cd7c)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_local.c (ffffffff8201c83d)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/ipv6/exthdrs_core.c (ffffffff82021699)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_icmp.c (ffffffff82022244)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff82022385)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/devlink/leftover.c (ffffffff82037794)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_nl_param_value_fill_one
  - net/devlink/leftover.c:devlink_nl_param_value_fill_one
  - net/devlink/leftover.c:devlink_dpipe_entry_ctx_close
  - net/devlink/leftover.c:devlink_dpipe_entry_ctx_close
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_entry_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_action_put
  - net/devlink/leftover.c:devlink_dpipe_action_put
  - net/devlink/leftover.c:devlink_dpipe_match_put
  - net/devlink/leftover.c:devlink_dpipe_match_put
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
```
```
In net/devlink/dev.c (ffffffff82045985)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/devlink/health.c (ffffffff8204845a)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/wireless/wext-core.c (ffffffff8204b0ab)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82050b17)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8205224c)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053ba5)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054d25)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff820593a1)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068d7f)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff82082235)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff82087ab2)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff8208dfb9)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff8208f346)
Location: include/linux/skbuff.h:2533
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82091980)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
```
In net/handshake/netlink.c (ffffffff82092531)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff82093f7f)
Location: include/linux/skbuff.h:2533
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
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
In kernel/audit.c (ffffffff81256ba7)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff8128069c)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
```
```
In kernel/bpf/core.c (ffffffff81306525)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In fs/quota/netlink.c (ffffffff81599c71)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff81a03476)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/regulator/event.c (ffffffff81ae2613)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - drivers/regulator/event.c:reg_generate_netlink_event
```
```
In drivers/net/virtio_net.c (ffffffff81d0bc9a)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable_xdp
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03ddd)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebb8eb)
Location: include/linux/skbuff.h:2540
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
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_dplls
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_dplls
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_dplls
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_parents
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_parents
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq
```
```
In net/core/skbuff.c (ffffffff81ed2f36)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff81ee0b4a)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (ffffffff81ee176b)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff81ef0c16)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81f075c5)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81f16761)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
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
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnl_port_fill
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnetlink_put_metrics
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
  - net/core/rtnetlink.c:rtnl_link_fill
```
```
In net/core/filter.c (ffffffff81f24f22)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/xdp.c (ffffffff81f3834b)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/core/gro.c (ffffffff81f3b956)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/netdev-genl.c (ffffffff81f3d214)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_fill_one
  - net/core/netdev-genl.c:netdev_nl_napi_fill_one
  - net/core/netdev-genl.c:netdev_nl_dev_fill
```
```
In net/core/page_pool_user.c (ffffffff81f45330)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_nl_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
  - net/core/page_pool_user.c:page_pool_nl_stats_fill
```
```
In net/core/fib_rules.c (ffffffff81f4a474)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81f5dc0c)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffff81f5fe12)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_fill_encap
  - net/core/lwtunnel.c:lwtunnel_fill_encap
```
```
In net/core/lwt_bpf.c (ffffffff81f605a5)
Location: include/linux/skbuff.h:2540
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6aea5)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:diag_get
```
```
In net/sched/sch_api.c (ffffffff81f75ebc)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f7a465)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_terse_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff81f82c10)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_dump_walker
  - net/sched/act_api.c:tcf_action_dump_terse
```
```
In net/sched/ematch.c (ffffffff81f85681)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff81f8bb51)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/netlink/genetlink.c (ffffffff81f8e75c)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_dumppolicy_put_op
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/netlink/policy.c (ffffffff81f9081d)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:netlink_policy_dump_write
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
  - net/netlink/policy.c:__netlink_policy_dump_write_attr
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2540
Inline: True
```
```
In net/ethtool/netlink.c (ffffffff81f9e205)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_fill_reply_header
  - net/ethtool/netlink.c:ethnl_fill_reply_header
```
```
In net/ethtool/bitset.c (ffffffff81f9ef60)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
```
```
In net/ethtool/strset.c (ffffffff81fa03cc)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
```
```
In net/ethtool/features.c (ffffffff81fa25ce)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ethtool/features.c:features_send_reply
```
```
In net/ethtool/pause.c (ffffffff81fa4e74)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81fa5e11)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_step
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_pulse
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_finished
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/tunnels.c (ffffffff81fa6d76)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
```
In net/ethtool/fec.c (ffffffff81fa7092)
Location: include/linux/skbuff.h:2540
Inline: True
```
```
In net/ethtool/stats.c (ffffffff81fa80dc)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_stats
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stats_put_rmon_hist
  - net/ethtool/stats.c:stat_put
  - net/ethtool/stats.c:stat_put
```
```
In net/ethtool/mm.c (ffffffff81fa97ad)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ipv4/route.c (ffffffff81fb0146)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc2882)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffc652)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffe45)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8200c662)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/icmp.c (ffffffff820122aa)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff82014068)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff8201d326)
Location: include/linux/skbuff.h:2540
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff820295bd)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82033df1)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
```
```
In net/ipv4/nexthop.c (ffffffff8203a028)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
```
```
In net/ipv4/ipmr.c (ffffffff8204635f)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:ipmr_fill_vif
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
```
```
In net/ipv4/ipmr_base.c (ffffffff820497e5)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/xfrm/xfrm_output.c (ffffffff820702c7)
Location: include/linux/skbuff.h:2540
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8208c5de)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff82098186)
Location: include/linux/skbuff.h:2540
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a08fe)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff820b23b6)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
```
In net/ipv6/icmp.c (ffffffff820bdf1f)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff820c14a7)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/datagram.c (ffffffff820d28de)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff820d662c)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ioam6.c (ffffffff820d7f42)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
```
In net/ipv6/ip6mr.c (ffffffff820dbd4c)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_local.c (ffffffff820eb66d)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:put_nla_counters
```
```
In net/ipv6/exthdrs_core.c (ffffffff820f07c9)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_icmp.c (ffffffff820f1364)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff820f14a5)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/devlink/netlink.c (ffffffff82101685)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_put_nested_handle
  - net/devlink/netlink.c:devlink_nl_put_nested_handle
```
```
In net/devlink/dev.c (ffffffff821052c8)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_selftests_fill
  - net/devlink/dev.c:devlink_nl_flash_update_fill
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_info_version_put
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/devlink/port.c (ffffffff82106994)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_fill
  - net/devlink/port.c:devlink_nl_port_function_attrs_put
  - net/devlink/port.c:devlink_nl_port_function_attrs_put
```
```
In net/devlink/sb.c (ffffffff8210892b)
Location: include/linux/skbuff.h:2540
Inline: True
```
```
In net/devlink/dpipe.c (ffffffff8210a48d)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_dpipe_entry_ctx_close
  - net/devlink/dpipe.c:devlink_dpipe_entry_ctx_close
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_entry_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_action_put
  - net/devlink/dpipe.c:devlink_dpipe_action_put
  - net/devlink/dpipe.c:devlink_dpipe_match_put
  - net/devlink/dpipe.c:devlink_dpipe_match_put
```
```
In net/devlink/resource.c (ffffffff8210c412)
Location: include/linux/skbuff.h:2540
Inline: True
```
```
In net/devlink/param.c (ffffffff8210dae3)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_value_fill_one
  - net/devlink/param.c:devlink_nl_param_value_fill_one
```
```
In net/devlink/region.c (ffffffff8211130c)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_notify_build
```
```
In net/devlink/health.c (ffffffff8211455f)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/devlink/trap.c (ffffffff82114bc4)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
```
In net/devlink/rate.c (ffffffff8211898f)
Location: include/linux/skbuff.h:2540
Inline: True
```
```
In net/devlink/linecard.c (ffffffff821199d4)
Location: include/linux/skbuff.h:2540
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8211d52b)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff821231c7)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82124a39)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126385)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82127605)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff8212bf21)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_getapptrust
  - net/dcb/dcbnl.c:dcbnl_getapptrust
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213bfff)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
```
In net/mptcp/diag.c (ffffffff8215781b)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff8215d30a)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_dumpit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff82164479)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff82165826)
Location: include/linux/skbuff.h:2540
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82167f20)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
```
```
In net/handshake/netlink.c (ffffffff82168e11)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff8216a89f)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
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
In kernel/audit.c (ffff8000101ea934)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffff80001020db8c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffff80001025d5a8)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In fs/quota/netlink.c (ffff800010437688)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffff800010778d2c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffff800010ad391c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffff800010bb8240)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffff800010bbf478)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (ffff800010bbfd28)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffff800010bcecb0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffff800010be3fc0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffff800010bf1810)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/filter.c (ffff800010bf726c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/fib_rules.c (ffff800010c12f84)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/drop_monitor.c (ffff800010c1c90c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffff800010c1e17c)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/lwt_bpf.c (ffff800010c1e7b8)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/devlink.c (ffff800010c2c0fc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffff800010c3cb18)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffff800010c4031c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
```
```
In net/sched/act_api.c (ffff800010c47724)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffff800010c49b74)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffff800010c4fc10)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffff800010c51c0c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/route.c (ffff800010c5753c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffff800010c69418)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92128)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/icmp.c (ffff800010ca49bc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffff800010ca5730)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9030)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/nexthop.c (ffff800010cc3884)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffff800010cc9f0c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffff800010cd0a58)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffff800010d02788)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffff800010d0b4bc)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/route.c (ffff800010d0de34)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffff800010d22b44)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffff800010d2bb48)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d2e0d8)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffff800010d3d6d0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffff800010d416f8)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffff800010d423a4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffff800010d50904)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/wireless/wext-core.c (ffff800010d60e3c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d66600)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d67a14)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d6975c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6a8a4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffff800010d6f3a8)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d9fc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/audit.c (c0429ad4)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (c044c578)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (c0490e4c)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:2170
Inline: True
```
```
In fs/quota/netlink.c (c05ff2ec)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/thermal/thermal_core.c (c0bb44dc)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (c0cd3614)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (c0cdaf24)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/net_namespace.c (c0cdb808)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (c0ce49ac)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (c0cfe44c)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (c0d09ff4)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/filter.c (c0d10344)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/fib_rules.c (0)
Location: include/linux/skbuff.h:2170
Inline: True
```
```
In net/core/drop_monitor.c (c0d34818)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (c0d35ce0)
Location: include/linux/skbuff.h:2170
Inline: True
```
```
In net/core/lwt_bpf.c (c0d367fc)
Location: include/linux/skbuff.h:2170
Inline: True
```
```
In net/core/devlink.c (c0d42c84)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_info_version_put
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (c0d4e870)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c0d52248)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (c0d58518)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (c0d5a910)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (c0d5fdec)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (c0d61304)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2170
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:2170
Inline: True
```
```
In net/ipv4/ip_sockglue.c (c0d78618)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (c0da0e3c)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (c0da3bcc)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (c0dadd3c)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/icmp.c (c0db0b00)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (c0db20a0)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
```
```
In net/ipv4/igmp.c (c0db9d28)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_sendpack
```
```
In net/ipv4/fib_semantics.c (c0dc47a0)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/nexthop.c (c0dcf060)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (c0dd5eb0)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (c0ddadb0)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (c0e08598)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (c0e114a0)
Location: include/linux/skbuff.h:2170
Inline: True
```
```
In net/ipv6/route.c (c0e1451c)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (c0e27ad8)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
```
In net/ipv6/icmp.c (c0e2f9b0)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e32bf8)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (c0e408c0)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (c0e440fc)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (c0e44ccc)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (c0e51464)
Location: include/linux/skbuff.h:2170
Inline: True
```
```
In net/ipv6/exthdrs_core.c (c0e539c4)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/output_core.c (c0e54498)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/wireless/wext-core.c (c0e605c4)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (c0e64e30)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_protocols_cb
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (c0e66588)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67d44)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c0e68e24)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (c0e6d014)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (c0e78558)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/audit.c (c00000000025bcd0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (c00000000028bc34)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (c000000000301fe4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In fs/quota/netlink.c (c000000000549ac8)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/thermal/thermal_core.c (c000000000bb8c20)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (c000000000c901f4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_put
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (c000000000c98774)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/net_namespace.c (c000000000c9915c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (c000000000ca5038)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (c000000000cc7394)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (c000000000cd63a0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/filter.c (c000000000cdccd0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/fib_rules.c (c000000000cfff78)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/drop_monitor.c (c000000000d0d8e0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (c000000000d0f8b0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/lwt_bpf.c (c000000000d10840)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/devlink.c (c000000000d22c14)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (c000000000d37be4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (c000000000d3afec)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (c000000000d445bc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (c000000000d47668)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (c000000000d4e720)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (c000000000d506dc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/route.c (c000000000d58a98)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (c000000000d6dff8)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (c000000000da290c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/icmp.c (c000000000db7c74)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (c000000000db9610)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/fib_semantics.c (c000000000dd1c54)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/nexthop.c (c000000000ddf4f8)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (c000000000de9364)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (c000000000deebd8)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (c000000000e2a038)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (c000000000e35b54)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/route.c (c000000000e39da0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (c000000000e52824)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (c000000000e5d154)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c000000000e61c58)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (c000000000e71a7c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (c000000000e75f84)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (c000000000e77188)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (c000000000e885d0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/wireless/wext-core.c (c000000000e9c228)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea27a0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea4314)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea65bc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7c3c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (c000000000eae230)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebd550)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/audit.c (ffffffe00015f34e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffe00016ea98)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffffffe00019bc36)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In fs/quota/netlink.c (ffffffe0002d18bc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In lib/nlattr.c (ffffffe00048e80e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve_64bit
```
```
In drivers/thermal/thermal_core.c (ffffffe0006cff1e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffe000747af0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffe00074cf10)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/net_namespace.c (ffffffe00074d5e0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffe00075514a)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffe00076a978)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffe000773558)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/filter.c (ffffffe0007790b6)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/fib_rules.c (ffffffe00078e944)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/drop_monitor.c (ffffffe00079681e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffe000797b6c)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffe000798446)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/devlink.c (ffffffe0007a36ee)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffe0007ad39c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007afd82)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffe0007b546c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffe0007b7234)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffe0007bb7b2)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffe0007bcd06)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/route.c (ffffffe0007c17d2)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf30a)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f20d0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/icmp.c (ffffffe0007ffcd6)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffe000800ff2)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffe00080fde8)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/nexthop.c (ffffffe000818ae6)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffe00081f3f4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffe000822586)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffe00084ab8a)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffe000852720)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/route.c (ffffffe0008558b4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffe00086463e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffe00086be5a)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffe00086eb36)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffffffe000879e2a)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffe00087cdcc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffe00087da2c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffe000888d32)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/wireless/wext-core.c (ffffffe000895f6a)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a0de)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b020)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089c690)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d440)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffe0008a0f3e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab218)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/audit.c (ffffffff8116e087)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff8118df30)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffffffff811d5222)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In fs/quota/netlink.c (ffffffff81366212)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815dc9d8)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8182c990)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffff818bdb66)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff818c3d0a)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/net_namespace.c (ffffffff818c43b9)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff818cc344)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff818e40f0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818efb11)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/filter.c (ffffffff818f544c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/fib_rules.c (ffffffff8190c6e1)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81916403)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffff819174b5)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81917d95)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/devlink.c (ffffffff8192390d)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff819306dc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81933c45)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8193a36c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff8193c712)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff8194140f)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff819427bc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/route.c (ffffffff81947ace)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff81957ed9)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197eda4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8198e485)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff8198f664)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819a07c9)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/nexthop.c (ffffffff819aa124)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff819b114e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff819b4974)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff819de936)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819e7871)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ea251)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff819fcf8b)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff81a05128)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a08023)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffffffff81a14376)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81a17803)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a1829e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff81a23f3f)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81a32694)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a363bc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a376da)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a3905d)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a03d)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a3dd63)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a490ce)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/audit.c (ffffffff81161227)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff81181040)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffffffff811c7fe2)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In fs/quota/netlink.c (ffffffff81356eb2)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815c8018)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/net/vxlan.c (ffffffff8176d8ac)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In drivers/thermal/thermal_core.c (ffffffff817f4020)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffff81877aa6)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff8187dc4a)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/net_namespace.c (ffffffff8187e2f9)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff818863d4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff8189df30)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff818a9951)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/filter.c (ffffffff818af27c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/fib_rules.c (ffffffff818c64a1)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff818d01b3)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffff818d1265)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff818d1b45)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/devlink.c (ffffffff818dd6bd)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff818ea1dc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff818ed745)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff818f3e6c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff818f6212)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff818faeff)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff818fc2ac)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/route.c (ffffffff819015be)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff819119c9)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938864)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81947f45)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff81949124)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a289)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/nexthop.c (ffffffff81963be4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967e1a)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv4/ipmr.c (ffffffff8196d77e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81970fa4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff8199b6f6)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a4631)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a7011)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff819b9d4b)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff819c1ee8)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c4de3)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffffffff819d1136)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff819d45c3)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff819d505e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff819e0cff)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff819ef884)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f2fdc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f42fa)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f5c7d)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6c5d)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819fa953)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05cbe)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/audit.c (ffffffff8116be57)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff8118bd00)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffffffff811d2ff2)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In fs/quota/netlink.c (ffffffff81363ce2)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815e1b68)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff8187bfc0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffff8190eb66)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff81914d0a)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/net_namespace.c (ffffffff819153b9)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff8191d344)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81935120)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81940b41)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/filter.c (ffffffff8194647c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/fib_rules.c (ffffffff8195d711)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81967433)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffff81968645)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81968f25)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/devlink.c (ffffffff81974a9d)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff8198186c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81984dd5)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff8198b4fc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff8198d8a2)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff8199259f)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff8199394c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199a550)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199c542)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/netfilter/nfnetlink_log.c:__build_packet_message
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a51eb)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_to_nlattr
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_to_nlattr
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a9a95)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:dccp_to_nlattr
  - net/netfilter/nf_conntrack_proto_dccp.c:dccp_to_nlattr
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aa685)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:sctp_to_nlattr
  - net/netfilter/nf_conntrack_proto_sctp.c:sctp_to_nlattr
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ae79b)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_stat_cpu_dump
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_expect_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_tuple
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_tuple
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_build
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_build
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_build
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_build
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_build
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_build
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_stat_ct
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_ct_stat_cpu_dump
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_fill_info
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_fill_info
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_fill_info
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_fill_info
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_fill_info
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_ct_synproxy
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_ct_synproxy
  - net/netfilter/nf_conntrack_netlink.c:dump_ct_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:dump_ct_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_timestamp
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_timestamp
  - net/netfilter/nf_conntrack_netlink.c:dump_counters
  - net/netfilter/nf_conntrack_netlink.c:dump_counters
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_helpinfo
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_helpinfo
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_protoinfo
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_protoinfo
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_tuples_ip
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_tuples_ip
```
```
In net/ipv4/route.c (ffffffff819b229e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c26a9)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9574)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819f8d25)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff819f9f04)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0b069)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/nexthop.c (ffffffff81a149c4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a1b9ee)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f214)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a493b6)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a522f1)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a54cd1)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a67a0b)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff81a6fba8)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a72aa3)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffffffff81a7edf6)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81a82283)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a82d1e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff81a8e9bf)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81a9e244)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa226c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa358a)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa4f0d)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa5eed)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81aa9c13)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4f7e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
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
In kernel/audit.c (ffffffff81179617)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_string
  - kernel/audit.c:audit_log_n_hex
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
```
```
In kernel/taskstats.c (ffffffff8119967d)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:mk_reply
  - kernel/taskstats.c:send_reply
```
```
In kernel/bpf/core.c (ffffffff811e12e2)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In fs/quota/netlink.c (ffffffff81377392)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In drivers/acpi/event.c (ffffffff815fba28)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/thermal/thermal_core.c (ffffffff818979f0)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/skbuff.c (ffffffff8192fc96)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_dump
```
```
In net/core/gen_stats.c (ffffffff81935eda)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/net_namespace.c (ffffffff81936599)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/dev.c (ffffffff8193e864)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81956830)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
```
```
In net/core/rtnetlink.c (ffffffff81962451)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
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
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vf
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
  - net/core/rtnetlink.c:rtnl_fill_vfinfo
```
```
In net/core/filter.c (ffffffff81967d6c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/fib_rules.c (ffffffff8197f961)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff819896c3)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_packet_report_in_port_put
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/lwtunnel.c (ffffffff8198a9ed)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff8198b305)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/core/devlink.c (ffffffff81996f8d)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_trap_stats_put
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_close
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff819a3ddb)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff819a75c5)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tcf_exts_dump
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/act_api.c (ffffffff819add6c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/sched/ematch.c (ffffffff819b01d2)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
  - net/sched/ematch.c:tcf_em_tree_dump
```
```
In net/netlink/af_netlink.c (ffffffff819b508f)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff819b643c)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:ctrl_fill_info
```
```
In net/bpf/test_run.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/route.c (ffffffff819bb95e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc0a9)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f32e4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81a02ca5)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (ffffffff81a04214)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a15849)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
```
```
In net/ipv4/nexthop.c (ffffffff81a1f3d4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
```
In net/ipv4/ipmr.c (ffffffff81a26939)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2a6e4)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
```
In net/ipv6/addrconf.c (ffffffff81a552d6)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e2e1)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a60cc1)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/ndisc.c (ffffffff81a73ffa)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/icmp.c (ffffffff81a7c1d2)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a7f123)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffffffff81a8b6b6)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81a8eb93)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f5ee)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b72f)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/skbuff.h:2153
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81aaa444)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae5dc)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aaf9aa)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab128d)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab228d)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81ab5f83)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_build_peer_app
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac131e)
Location: include/linux/skbuff.h:2153
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
```
</details>
</li>
</ul>

## Differences
