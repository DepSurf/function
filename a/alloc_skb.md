# Function: <code>alloc_skb</code>

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
In kernel/audit.c (ffffffff811217c3)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8113e200)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff812766c6)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff8132e113)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
```
```
In security/selinux/netlink.c (ffffffff8134cb22)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/kobject_uevent.c (ffffffff813ece9a)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
```
In drivers/acpi/event.c (ffffffff81489729)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81541daa)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/virtio_net.c (ffffffff815f3651)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f5db1)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffff81685889)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffff817025b3)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff81706d7e)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/net_namespace.c (ffffffff8170ff06)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81726db6)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
```
```
In net/core/rtnetlink.c (ffffffff8172a56b)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
```
```
In net/core/sock_diag.c (ffffffff817331f6)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff81738094)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/fib_rules.c (ffffffff8173a28c)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/sched/sch_api.c (ffffffff81743a3b)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/sched/sch_api.c:tclass_notify
  - net/sched/sch_api.c:qdisc_notify
```
```
In net/sched/cls_api.c (ffffffff8174645c)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/sched/cls_api.c:tfilter_notify
```
```
In net/sched/act_api.c (ffffffff8174712b)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff8174b204)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/af_netlink.c:__netlink_alloc_skb
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/netlink/genetlink.c (ffffffff8175000e)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:genl_ctrl_event
```
```
In net/ipv4/route.c (ffffffff81757271)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_fragment.c (ffffffff8175a12a)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8175c976)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761a1f)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff8176e5dc)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81774acb)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781658)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff8178bac6)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff81790509)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
```
In net/ipv4/igmp.c (ffffffff81796182)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/fib_semantics.c (ffffffff8179dd41)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff817a7309)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:mroute_netlink_event
```
```
In net/ipv6/ip6_output.c (ffffffff817c7514)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/addrconf.c (ffffffff817cc3fe)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
```
```
In net/ipv6/addrlabel.c (ffffffff817d2f7f)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff817d8cf2)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rt_notify
```
```
In net/ipv6/ndisc.c (ffffffff817de806)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/reassembly.c (ffffffff817ee4ef)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817eeeef)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff817f4b87)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
```
```
In net/ipv6/ip6mr.c (ffffffff817f84d7)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
```
```
In net/wireless/wext-core.c (ffffffff81809d45)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d3c6)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e526)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180fe59)
Location: include/linux/skbuff.h:812
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81813cdb)
Location: include/linux/skbuff.h:812
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
In kernel/audit.c (ffffffff81129756)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8114685e)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff812a2f06)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff81362da0)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
```
```
In security/selinux/netlink.c (ffffffff81382ac2)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/kobject_uevent.c (ffffffff81433259)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
```
In drivers/acpi/event.c (ffffffff814d851f)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff815936ea)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/virtio_net.c (ffffffff816534af)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81657947)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffff816e6d5f)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffff817697e3)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff8176e1ae)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/net_namespace.c (ffffffff81777846)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff817908d6)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
```
```
In net/core/rtnetlink.c (ffffffff8179670d)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff8179ec16)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff817a55b3)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff817a63fc)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/sched/sch_api.c (ffffffff817b089b)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/sched/sch_api.c:tclass_notify
  - net/sched/sch_api.c:qdisc_notify
```
```
In net/sched/cls_api.c (ffffffff817b346c)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/sched/cls_api.c:tfilter_notify
```
```
In net/sched/act_api.c (ffffffff817b5ded)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff817bac6f)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff817bc326)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (ffffffff817c3511)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_fragment.c (ffffffff817c6543)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817c9762)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cdd4f)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp_input.c (ffffffff817da598)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff817e52f6)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff817eeb18)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff817f90d5)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff817fd989)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff818047eb)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b881)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff81815fc6)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff8183470f)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/addrconf.c (ffffffff81838e4e)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8184097f)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81847186)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff8184f0c9)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/reassembly.c (ffffffff8185cd2b)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185d7da)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81863d93)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/ip6mr.c (ffffffff81868e46)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff8187b845)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187f7b6)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880ba6)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882530)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8188353b)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81886bbb)
Location: include/linux/skbuff.h:909
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffffffff8188c3c8)
Location: include/linux/skbuff.h:909
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/audit.c (ffffffff81133880)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8115073e)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff812b88e6)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff81379580)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
```
```
In security/selinux/netlink.c (ffffffff81399542)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/kobject_uevent.c (ffffffff8144f4c9)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
```
In drivers/acpi/event.c (ffffffff814fac07)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff815c0faa)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81685627)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffff817161af)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffff81796703)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff8179b5ee)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/net_namespace.c (ffffffff817a48c6)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff817be186)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
```
```
In net/core/rtnetlink.c (ffffffff817c4d6a)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff817cd5e6)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff817d4023)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff818c4856)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/sched/sch_api.c (ffffffff817dffdb)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/sched/sch_api.c:tclass_notify
  - net/sched/sch_api.c:qdisc_notify
```
```
In net/sched/cls_api.c (ffffffff817e2cf5)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tfilter_notify
```
```
In net/sched/act_api.c (ffffffff817e5803)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff817ea60f)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff817ebc36)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (ffffffff817f2b05)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_fragment.c (ffffffff817f6043)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817f96eb)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdaaf)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff81807156)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81808f1d)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81815786)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f528)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff81829fa5)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff8182e8e9)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff818357c0)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c9a1)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff81847776)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81866168)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/addrconf.c (ffffffff8186a86e)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff818725ff)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81878fc6)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ndisc.c (ffffffff8188101f)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/reassembly.c (ffffffff8188ec69)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188f826)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81896443)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81899c46)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff8189bc96)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff818b0105)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b4066)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b5456)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6de0)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7ddb)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff818bb42b)
Location: include/linux/skbuff.h:923
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffffffff818c0577)
Location: include/linux/skbuff.h:923
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/audit.c (ffffffff81134d74)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81152d2e)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff812c5cb6)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff8138c39e)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff813af9b6)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff8150a145)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff815d6af9)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169aa47)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffff8172dfaf)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffff817b4ad3)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff817bd150)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
```
```
In net/core/net_namespace.c (ffffffff817c29f6)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff817dcc0b)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
```
```
In net/core/rtnetlink.c (ffffffff817e37c4)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff817ec95f)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff817f3380)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff817f4337)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/sched/sch_api.c (ffffffff817ff60d)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/sched/sch_api.c:tclass_notify
  - net/sched/sch_api.c:qdisc_notify
```
```
In net/sched/cls_api.c (ffffffff818026f2)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/sched/cls_api.c:tfilter_notify
```
```
In net/sched/act_api.c (ffffffff8180530a)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff8180a337)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff8180bb83)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (ffffffff818133f9)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_fragment.c (ffffffff81816482)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81819b02)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181def0)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff81827746)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff818291da)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81835b96)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff8184024f)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff8184b208)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff8184fa15)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff81856cf4)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e140)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff8186b06f)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff8188ab2d)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/addrconf.c (ffffffff8188edae)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81897385)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff8189e20b)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff818a7053)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/reassembly.c (ffffffff818b511f)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b5e9f)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff818bc9d7)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff818bfe36)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff818c2088)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff818d6ab4)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818daa16)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dbda6)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd69d)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de6ab)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff818e1e1b)
Location: include/linux/skbuff.h:900
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffffffff818e6ee9)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff818ef6be)
Location: include/linux/skbuff.h:900
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff81141ac4)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8115f54e)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff812e9b66)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff813b174e)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff813d5a66)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff8154c645)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff8163d8d9)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817051f7)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffff8179f5df)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffff8182de4b)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff81833b30)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
```
```
In net/core/net_namespace.c (ffffffff8183c336)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff818577db)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
```
```
In net/core/rtnetlink.c (ffffffff8185e6fd)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81868b3f)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff8186e770)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff8186fa9a)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/sched/sch_api.c (ffffffff8187e5df)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:qdisc_notify
```
```
In net/sched/cls_api.c (ffffffff8188114e)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
```
In net/sched/act_api.c (ffffffff81884024)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff818892f3)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff8188ab13)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (ffffffff81892a49)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_fragment.c (ffffffff8189561c)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81898137)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189ce00)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff818a6c96)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff818ae214)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff818b5196)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf5ef)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff818cae78)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff818cf645)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff818d6ba4)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff818de180)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff818eb80f)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff8190bd27)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/addrconf.c (ffffffff819103fe)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81917fd0)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff819207eb)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81929ab2)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/reassembly.c (ffffffff81937e95)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938c45)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff8193faf7)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81942f06)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff819459c8)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/strparser/strparser.c (ffffffff8195b492)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/wireless/wext-core.c (ffffffff8195c684)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819605f6)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961986)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8196328d)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819642b1)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81967bbb)
Location: include/linux/skbuff.h:980
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffffffff8196c399)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff81975b5c)
Location: include/linux/skbuff.h:980
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff81150479)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8116e565)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff81316a9f)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff813e1779)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff81406085)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff81582d75)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81678ef4)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817439ab)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffff817e6bda)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffff81878239)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff8187dfce)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/net_namespace.c (ffffffff81886d95)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff818a2981)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
```
```
In net/core/rtnetlink.c (ffffffff818aa2b7)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff818b89c7)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff818bf941)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff818c128a)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/sched/sch_api.c (ffffffff818d10d2)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff818d40e2)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
```
In net/sched/act_api.c (ffffffff818d7b77)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff818dcd75)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff818de145)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (ffffffff818e6afe)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_fragment.c (ffffffff818e97f4)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff818ec43d)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f12fc)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff818fbdc6)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff819038e3)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff8190a715)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff819151ec)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff81921387)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff81926085)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff8192d510)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81934cf0)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff81941789)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81962de4)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/addrconf.c (ffffffff8196784e)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8196f810)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81978b27)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81981c8a)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/reassembly.c (ffffffff81991019)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819924f2)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81998933)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff8199b803)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff8199d298)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/strparser/strparser.c (ffffffff819b4909)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/wireless/wext-core.c (ffffffff819b5e7f)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819b9de7)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb157)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcad6)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bdb51)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819c13c5)
Location: include/linux/skbuff.h:984
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819c5e4e)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cb24f)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In lib/kobject_uevent.c (ffffffff819d1d3d)
Location: include/linux/skbuff.h:984
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (ffffffff8115d139)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8117c035)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff8132da4f)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff813fc349)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff81421bd5)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff8159aea5)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81697fd4)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8176821b)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffff81812f8a)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffff81898719)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff8189eb8c)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/net_namespace.c (ffffffff818a7519)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff818c5b91)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff818ce9a7)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff818df617)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff818e8761)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff818ea09a)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/sched/sch_api.c (ffffffff818fc41a)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff818fec60)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
```
In net/sched/act_api.c (ffffffff81904219)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff8190974b)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff8190ab05)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (ffffffff819139c4)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_fragment.c (ffffffff819168a1)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff819195d4)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191ee5c)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff81929d46)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81931a80)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff819389b5)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194380c)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff81950197)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff819550a5)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff8195c9b0)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81964640)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ipmr.c (ffffffff81971e10)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81997dcd)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/addrconf.c (ffffffff8199cf36)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a5420)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff819ae7a7)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff819b8336)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/reassembly.c (ffffffff819c7772)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8c32)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff819cf293)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff819d21d3)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff819d3df8)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/strparser/strparser.c (ffffffff819eb911)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
```
```
In net/wireless/wext-core.c (ffffffff819ed13f)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f10b7)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f23c7)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3d28)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4cf1)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819f8925)
Location: include/linux/skbuff.h:1008
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819fd578)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a04205)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In lib/kobject_uevent.c (ffffffff81a0ae1d)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (ffffffff81169867)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81188ec5)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (ffffffff81332034)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/quota/netlink.c (ffffffff8135578e)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff81428f93)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff8144f7be)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff815cc515)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff816d0b54)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a5588)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffff81855020)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffff818e2ccf)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff818e93c9)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff818f25ba)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81911be0)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff8191b7b7)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff8192dc95)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff81937f73)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff81939afa)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/devlink.c (ffffffff81951b96)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffffffff8195bdab)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff8195e65b)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff8196535b)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff8196aa57)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff8196befd)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (ffffffff8197607b)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8197b299)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff8198177d)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff8198cf66)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff8199516c)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff8199b8f5)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7ddb)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff819b4a57)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff819b994a)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff819c16b6)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff819ca19d)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf3b9)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff819d4b3b)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff819db6a5)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81a01332)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff81a09116)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a118ff)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81a1d033)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81a26d8b)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a375bd)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81a3dfe2)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81a41003)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a42508)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a5c330)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a60377)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a61717)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a63188)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a641b1)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a67be5)
Location: include/linux/skbuff.h:1052
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81a6c7da)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a734a5)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In lib/kobject_uevent.c (ffffffff81a7a7fb)
Location: include/linux/skbuff.h:1052
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (ffffffff81175707)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81194e05)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (ffffffff81345bf4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/quota/netlink.c (ffffffff8136dace)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff81442cc3)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff8146962e)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff815ed795)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff816f4974)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c9688)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffff81886a80)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffff81914eaf)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff8191b529)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff81924527)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81944250)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff8194ddf4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff8195fee9)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff8196ae33)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff8196c9ca)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff819763b9)
Location: include/linux/skbuff.h:1048
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
In net/core/devlink.c (ffffffff819885d6)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffffffff819922af)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff81994f2b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff8199bf24)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff819a14e9)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff819a28ad)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (ffffffff819aca8b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff819b1c09)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b7fbd)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff819c3906)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff819cbcbc)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff819d2315)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff819dee6b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff819eb787)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff819f063e)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff819f8256)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00d6d)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05f4b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff81a0b6a1)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81a125be)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81a37f12)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff81a3fdc6)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a4851f)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81a53d03)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81a5d7f1)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e0e7)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81a74c52)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81a77c83)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a79168)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a92f60)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a96fa7)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a982e7)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a99d38)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9ad31)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a9e545)
Location: include/linux/skbuff.h:1048
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aa319a)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa9c95)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In lib/kobject_uevent.c (ffffffff81ab1b5b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (ffffffff8118656c)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff811a9f95)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (ffffffff8137ebad)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/quota/netlink.c (ffffffff813b55fe)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff814935c3)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff814bd7d5)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/kobject_uevent.c (ffffffff815ec1eb)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
```
```
In drivers/acpi/event.c (ffffffff81699315)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff817acfa4)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81893bf8)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In net/core/sock.c (ffffffff819e7fcf)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff819ee399)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff819f81d7)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81a142c0)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81a1f97a)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81a337b9)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff81a3eb95)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff81a4088a)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81a4b285)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81a515ff)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffffffff81a6a714)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff81a6dc5b)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff81a74d84)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81a7aec7)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/netlink/genetlink.c (ffffffff81a7d619)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a86746)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81a8cf68)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/route.c (ffffffff81a922d5)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a9d9d3)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa28dd)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff81aaf086)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81ab1f38)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81abf075)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc405)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff81ad9867)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff81ade5ac)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff81ae51f1)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81aefdd0)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/inet_fragment.c (ffffffff81af565b)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff81afc0cf)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81b048ef)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81b2df22)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff81b3dd20)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f3ad)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81b4b393)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81b53b06)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67de3)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81b6eea2)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81b72203)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81b744b4)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81b8e270)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92827)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93b57)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b957b8)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b964ff)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81b995c5)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9e532)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_alloc_command
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5e95)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb35fb)
Location: include/linux/skbuff.h:1080
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In kernel/audit.c (ffffffff8118365c)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff811a75b8)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (ffffffff8138e0cd)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/quota/netlink.c (ffffffff813c6e2e)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff814b0ec3)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff814db251)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/kobject_uevent.c (ffffffff816109cb)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
```
```
In drivers/acpi/event.c (ffffffff816b63d5)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff817c1b34)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a2098)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_netlink.c (ffffffff8195f6e3)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/sock.c (ffffffff819e7a9f)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff819ee039)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff819f7bd7)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81a145d0)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81a1f3da)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81a35b29)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff81a41935)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff81a435aa)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81a50eb5)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/devlink.c (ffffffff81a5770f)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffffffff81a72e61)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff81a7662f)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff81a7db84)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81a83c87)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/netlink/genetlink.c (ffffffff81a861d9)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a90056)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81a966a8)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/route.c (ffffffff81a9c175)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81aa7896)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacbed)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff81aba13b)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81abcf00)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81aca9d5)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad83c7)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff81ae62b7)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff81aeb38c)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff81af20c3)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81afcd10)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/inet_fragment.c (ffffffff81b0241b)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff81b0996f)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81b12a60)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c972)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff81b4c8b0)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b4de3d)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81b5a039)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81b620f6)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b76612)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81b7d9d2)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81b80f63)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81b83224)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81b9df10)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba2477)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba3797)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba540b)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba616f)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81ba9275)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81badf32)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_alloc_command
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb5375)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7ce0)
Location: include/linux/skbuff.h:1096
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In kernel/audit.c (ffffffff81186012)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff811a7f98)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (ffffffff8139404d)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/quota/netlink.c (ffffffff813cdebe)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff814b6d33)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff814e1bb5)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/kobject_uevent.c (ffffffff815f408d)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
```
```
In drivers/acpi/event.c (ffffffff81698485)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff817a5052)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81884368)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81887f21)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81942c43)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/sock.c (ffffffff819cda6f)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff819d78d9)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff819ddd5a)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff819faf60)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81a0647d)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81a1cc79)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff81a263f5)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff81a2830a)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81a35cd9)
Location: include/linux/skbuff.h:1104
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
In net/core/devlink.c (ffffffff81a4be95)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffffffff81a5b796)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff81a5e52f)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff81a669a0)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81a6ce46)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff81a6eee9)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81a79767)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81a80188)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/route.c (ffffffff81a87165)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a92a89)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a97e3d)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff81aa53c0)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81aa7d51)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81ab59c5)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac315f)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff81ad1597)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff81ad80b8)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff81add8b3)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae864e)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81aea935)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/inet_fragment.c (ffffffff81aedd2b)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff81af895d)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81b00180)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81b29de2)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff81b31f33)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b8dd)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81b419c5)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81b50356)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b64f44)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81b6c5c2)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81b6fb73)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81b71ea5)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81b8d010)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b91557)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b928b7)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b94566)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b952ef)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81b98405)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9d73a)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba4375)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbb96a)
Location: include/linux/skbuff.h:1104
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In kernel/audit.c (ffffffff811ae402)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff811d1d58)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (ffffffff813e1b1d)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/quota/netlink.c (ffffffff8141f1ee)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff8150f673)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff8153abb5)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In lib/kobject_uevent.c (ffffffff816613fd)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
```
```
In drivers/acpi/event.c (ffffffff8170e205)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff818309d2)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81915d28)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191a8ff)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
```
```
In drivers/thermal/thermal_netlink.c (ffffffff819e7705)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/sock.c (ffffffff81a7d27f)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff81a86119)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff81a8dfea)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81aacba0)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81ab8afd)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81ad04d9)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/sock_reuseport.c (ffffffff81ad1c5a)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/netpoll.c (ffffffff81adb16c)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff81add0aa)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81aeb8a9)
Location: include/linux/skbuff.h:1116
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
In net/core/devlink.c (ffffffff81b0428c)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_doit
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffffffff81b14956)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff81b17710)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff81b1fe1b)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81b264c6)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff81b28929)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
```
```
In net/ethtool/netlink.c (ffffffff81b33ae8)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81b39f58)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/route.c (ffffffff81b41925)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4de8e)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b532cd)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff81b61710)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81b64137)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81b72a05)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b80fd0)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff81b901c7)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff81b96f18)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff81b9cd23)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba85dd)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81ba9cc6)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae0db)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff81bb748d)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81bc12b0)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81bef9b2)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff81bf8003)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81c0216d)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81c096f2)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81c17606)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d184)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81c34496)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81c37cc3)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c355)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81c593c7)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5dcf7)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f057)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60d46)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61b1f)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81c64f55)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81c6acb0)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c71f05)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b5aa)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
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
In kernel/audit.c (ffffffff811df62e)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81206578)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff8149702f)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff815a296b)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff815d22f5)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In io_uring/io_uring.c (ffffffff816d3c1a)
Location: include/linux/skbuff.h:1423
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff8177b19d)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
```
```
In drivers/acpi/event.c (ffffffff8183cbd5)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81971d68)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6c1ab)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fd42)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
```
```
In drivers/net/xen-netfront.c (ffffffff81a74ecd)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:bounce_skb
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81b4cfb5)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/sock.c (ffffffff81bf089d)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff81bf88e8)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff81c03c5a)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81c25b91)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81c33b40)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81c4dd8a)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/sock_reuseport.c (ffffffff81c4f50f)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/netpoll.c (ffffffff81c5c646)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff81c5e8ea)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81c6e1e9)
Location: include/linux/skbuff.h:1423
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
In net/core/devlink.c (ffffffff81c89bf9)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_doit
  - net/core/devlink.c:devlink_linecard_notify
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_doit
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffffffff81c9bd16)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff81c9f4cf)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff81ca7cdf)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81caf02e)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff81cb1a15)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ethtool/netlink.c (ffffffff81cbf215)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81cc5e18)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/route.c (ffffffff81cd33a4)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81cdb675)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdf9ef)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff81cf013a)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81cf2fe2)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81d020b5)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1144a)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff81d215d7)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff81d28ab3)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff81d2edf2)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3afe7)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81d3c8bd)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41212)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff81d4b1bc)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81d55c7a)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81d88512)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff81d913a3)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c10c)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81da4880)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81db33f6)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca5a2)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81dd1d94)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81dd5883)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81dda70f)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81dfab5e)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81dfffb7)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e01407)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e032b6)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e0411f)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81e07b45)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81e0e40d)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15a95)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32b5f)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
```
In net/mctp/device.c (ffffffff81e38050)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_addr_notify
```
```
In net/mctp/route.c (ffffffff81e390c2)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
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
In kernel/audit.c (ffffffff8122530e)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8124e888)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff8152b03f)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff8164c48b)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff816801b5)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In io_uring/rsrc.c (ffffffff817a14e1)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In drivers/acpi/event.c (ffffffff81972625)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81adcfe8)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bff0fb)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02bd2)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
```
```
In drivers/net/xen-netfront.c (ffffffff81c06c19)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4cb5)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/sock.c (ffffffff81d9ce4d)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff81da7778)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff81db331a)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81dd7de1)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81de6f90)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81e02e8a)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/sock_reuseport.c (ffffffff81e04af7)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/netpoll.c (ffffffff81e12d36)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff81e1515a)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81e25e69)
Location: include/linux/skbuff.h:1267
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
In net/core/devlink.c (ffffffff81e447d9)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify_build
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_cmd_selftests_get_doit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_doit
  - net/core/devlink.c:devlink_linecard_notify
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_doit
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffffffff81e58223)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff81e5b71f)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff81e64a8f)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81e6c72a)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/netlink/genetlink.c (ffffffff81e6f855)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ethtool/netlink.c (ffffffff81e7ddb5)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81e853e8)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/route.c (ffffffff81e93594)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81e9bfde)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9fd8f)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff81eb346a)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81eb7612)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81ec7255)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed71fa)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff81ee89e7)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff81ef0503)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff81ef6e52)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81f03967)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81f0535d)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09fc2)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff81f148dc)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81f1fffa)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81f561d2)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff81f5fb03)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81f6addc)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81f73d20)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81f82d56)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b5dc)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81fa31e4)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81fa7023)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81fad345)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81fcf377)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd4dd7)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6257)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd8236)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd90ef)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81fdd085)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81fe484d)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81feca45)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff8200b5bf)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
```
In net/mctp/device.c (ffffffff82011290)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_addr_notify
```
```
In net/mctp/route.c (ffffffff820123e2)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
```
```
In lib/kobject_uevent.c (ffffffff8202439d)
Location: include/linux/skbuff.h:1267
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (ffffffff8123b8de)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81265c38)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff815633cf)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff81684bd1)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff816b8295)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In io_uring/rsrc.c (ffffffff817e26e1)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In drivers/acpi/event.c (ffffffff819b8cf5)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81b2b258)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/virtio_net.c (ffffffff81c55bd4)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6475b)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c68282)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
```
```
In drivers/net/xen-netfront.c (ffffffff81c6c310)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d285)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In net/core/sock.c (ffffffff81e0b69f)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff81e1980c)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff81e239da)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81e48b51)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81e57f80)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81e753e7)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/sock_reuseport.c (ffffffff81e7733b)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/netdev-genl.c (ffffffff81e7d0e2)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
```
```
In net/core/netpoll.c (ffffffff81e86656)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff81e88a6a)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81e9b409)
Location: include/linux/skbuff.h:1286
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
In net/sched/sch_api.c (ffffffff81eb3bfe)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff81eb7e7f)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff81ec09df)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81ec878a)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/netlink/genetlink.c (ffffffff81ecbcd5)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ethtool/netlink.c (ffffffff81eda375)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81ee1d18)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/route.c (ffffffff81ef1d34)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81efaa97)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe5df)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff81f11b8a)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81f15cf1)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81f25b15)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f361db)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff81f483a7)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff81f4ff53)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff81f568cf)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63347)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff81f64d5f)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69ad1)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff81f745ac)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81f7fafa)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5bb2)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff81fbf833)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81fcae0c)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81fd3e00)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff81fe3056)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffb9fb)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff82003a9a)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff82007883)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff8200db05)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/devlink/leftover.c (ffffffff820379f3)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_trap_policer_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_region_get_doit
  - net/devlink/leftover.c:devlink_nl_region_notify_build
  - net/devlink/leftover.c:devlink_nl_cmd_param_get_doit
  - net/devlink/leftover.c:devlink_dpipe_send_and_alloc_skb
  - net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_pool_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_sb_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_linecard_get_doit
  - net/devlink/leftover.c:devlink_linecard_notify
  - net/devlink/leftover.c:devlink_nl_cmd_port_new_doit
  - net/devlink/leftover.c:devlink_nl_cmd_port_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_rate_get_doit
  - net/devlink/leftover.c:devlink_rate_notify
  - net/devlink/leftover.c:devlink_port_notify
```
```
In net/devlink/dev.c (ffffffff820458d2)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_cmd_selftests_get_doit
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:devlink_nl_cmd_info_get_doit
  - net/devlink/dev.c:devlink_nl_cmd_eswitch_get_doit
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_get_doit
  - net/devlink/dev.c:devlink_notify
```
```
In net/devlink/health.c (ffffffff82047eea)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_get_doit
```
```
In net/wireless/wext-core.c (ffffffff8204aff3)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82050a77)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82051f17)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053f06)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054dbf)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff82059155)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82060b5d)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068ce5)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff82087a4f)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
```
In net/mctp/device.c (ffffffff8208e050)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_addr_notify
```
```
In net/mctp/route.c (ffffffff8208f1d2)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
```
```
In net/handshake/netlink.c (ffffffff820924c6)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff82093e7e)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_accept
```
```
In lib/kobject_uevent.c (ffffffff820a44ad)
Location: include/linux/skbuff.h:1286
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (ffffffff8125579e)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8127faf8)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/quota/netlink.c (ffffffff81599abf)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff816c1011)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff816f4cc5)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff81a03325)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/regulator/event.c (ffffffff81ae2515)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - drivers/regulator/event.c:reg_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81b825ec)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/virtio_net.c (ffffffff81d0c27a)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1b17b)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/net/xen-netfront.c (ffffffff81d20cc0)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/thermal/thermal_netlink.c (ffffffff81e03d75)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81ebb6bd)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
```
```
In net/core/sock.c (ffffffff81ec8093)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff81ed6c6e)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff81ee193a)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81f07711)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81f172d0)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
```
```
In net/core/sock_diag.c (ffffffff81f34c87)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/sock_reuseport.c (ffffffff81f372fb)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/netdev-genl.c (ffffffff81f3dfcd)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_napi_get_doit
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
  - net/core/netdev-genl.c:netdev_genl_dev_notify
```
```
In net/core/page_pool_user.c (ffffffff81f4557a)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/core/page_pool_user.c:netdev_nl_page_pool_event
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_do
```
```
In net/core/netpoll.c (ffffffff81f48663)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff81f4aa7a)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81f5db79)
Location: include/linux/skbuff.h:1293
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
In net/sched/sch_api.c (ffffffff81f763a4)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f7ae98)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_del_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff81f83647)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (ffffffff81f8baa4)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/netlink/genetlink.c (ffffffff81f8f1f5)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ethtool/netlink.c (ffffffff81f9e146)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
```
```
In net/ethtool/cabletest.c (ffffffff81fa5ba8)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/route.c (ffffffff81fb5e84)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81fbe9e6)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc2802)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff81fd5e2a)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81fda0c5)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81fea4d5)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffc47b)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff8200e504)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff82016103)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff8201cd7c)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff82029917)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/fib_trie.c (ffffffff8202b32f)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
```
In net/ipv4/inet_fragment.c (ffffffff82030151)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff8203ad4c)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff8204617a)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff82083282)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff8208ccd3)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff820985ac)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff820a1710)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
```
In net/ipv6/ndisc.c (ffffffff820b0f76)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ca116)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff820d284a)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff820d6713)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff820dd585)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/devlink/netlink.c (ffffffff82101804)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_msg_reply_and_new
```
```
In net/devlink/dev.c (ffffffff82105215)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_get_doit
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:devlink_nl_info_get_doit
  - net/devlink/dev.c:devlink_nl_eswitch_get_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_get_doit
```
```
In net/devlink/port.c (ffffffff8210807a)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_new_doit
  - net/devlink/port.c:devlink_nl_port_get_doit
  - net/devlink/port.c:devlink_port_notify
```
```
In net/devlink/sb.c (ffffffff82109f95)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_doit
  - net/devlink/sb.c:devlink_nl_sb_port_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_get_doit
```
```
In net/devlink/dpipe.c (ffffffff8210a704)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_dpipe_send_and_alloc_skb
```
```
In net/devlink/param.c (ffffffff8210f059)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_get_doit
```
```
In net/devlink/region.c (ffffffff821107e4)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_get_doit
  - net/devlink/region.c:devlink_nl_region_notify_build
```
```
In net/devlink/health.c (ffffffff82113f3a)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_get_doit
```
```
In net/devlink/trap.c (ffffffff821175f3)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_get_doit
  - net/devlink/trap.c:devlink_nl_trap_group_get_doit
  - net/devlink/trap.c:devlink_nl_trap_get_doit
```
```
In net/devlink/rate.c (ffffffff821191ce)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_nl_rate_get_doit
  - net/devlink/rate.c:devlink_rate_notify
```
```
In net/devlink/linecard.c (ffffffff8211a624)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/devlink/linecard.c:devlink_nl_linecard_get_doit
  - net/devlink/linecard.c:devlink_linecard_notify
```
```
In net/wireless/wext-core.c (ffffffff8211d473)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82123127)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff821246f7)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff821266e6)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8212769f)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff8212bcd5)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82133a7a)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213bf65)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/mptcp/pm_netlink.c (ffffffff8215d2af)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
```
```
In net/mctp/device.c (ffffffff82164510)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_addr_notify
```
```
In net/mctp/route.c (ffffffff821656b2)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
```
```
In net/handshake/netlink.c (ffffffff82168da6)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_genl_notify
```
```
In net/handshake/tlshd.c (ffffffff8216a79e)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_accept
```
```
In lib/kobject_uevent.c (ffffffff8217c57d)
Location: include/linux/skbuff.h:1293
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (ffff8000101ea560)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffff80001020d2e8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (ffff800010403bf0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
```
```
In fs/quota/netlink.c (ffff80001043752c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffff80001052c0e0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffff800010557ab0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffff800010778c88)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffff8000108ddd58)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a03bd8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffff800010ad3898)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffff800010badc58)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffff800010bb59fc)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffff800010bbfecc)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffff800010be411c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffff800010befd3c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffff800010c03718)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffff800010c114a8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffff800010c131d8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffff800010c1c86c)
Location: include/linux/skbuff.h:1048
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
In net/core/devlink.c (ffff800010c304f8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffff800010c3e7ac)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffff800010c41ab4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffff800010c490b0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffff800010c4fb3c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffff800010c51b7c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (ffff800010c5cbd4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffff800010c6253c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffff800010c693b0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffff800010c764e4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffff800010c7e944)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffff800010c84ea4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffff800010c9202c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffff800010ca131c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffff800010ca6490)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffff800010cafe68)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9360)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/inet_fragment.c (ffff800010cbeef8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffff800010cc4c8c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffff800010ccb290)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffff800010cf8704)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffff800010d01050)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffff800010d0b880)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffff800010d17e18)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffff800010d22a8c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37af4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffff800010d3d65c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffff800010d412b8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffff800010d4266c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffff800010d60d84)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d6656c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d679ac)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d697e8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6a92c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffff800010d6ef58)
Location: include/linux/skbuff.h:1048
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffff800010d74c44)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d990)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In lib/kobject_uevent.c (ffff800010d8bec8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (c042a2b4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (c044bc64)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (c05d7ac4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/quota/netlink.c (c05ff180)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (c06e41e0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (c070c9d0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (c09ccdc0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (c0ade934)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (c0bb444c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (c0ccb77c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (c0cd2a38)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (c0cdb9d4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (c0cfe5c8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (c0d0837c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (c0d1caac)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (c0d2935c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (c0d2ab94)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (c0d34750)
Location: include/linux/skbuff.h:1048
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
In net/core/devlink.c (c0d474e8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (c0d5023c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:qdisc_notify
```
```
In net/sched/cls_api.c (c0d538d0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (c0d59ed8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
```
In net/netlink/af_netlink.c (c0d5fd28)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (c0d61264)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (c0d6c32c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (c0d73c78)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (c0d78588)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (c0d84c00)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (c0d8d930)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (c0d9418c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (c0da0d44)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (c0dae1e8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (c0db2f88)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (c0dbb81c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (c0dc4b00)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/inet_fragment.c (c0dca680)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (c0dd0704)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (c0dd6bd4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (c0e01250)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (c0e08b84)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (c0e11780)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (c0e1d9ec)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (c0e27030)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/tcp_ipv6.c (c0e38700)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (c0e40840)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (c0e43cc0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (c0e4508c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c0e60414)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (c0e64dac)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (c0e6634c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67dd0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c0e68ec4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (c0e6cc0c)
Location: include/linux/skbuff.h:1048
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (c0e7171c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (c0e784b8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In lib/kobject_uevent.c (c0e86280)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (c00000000025b750)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (c00000000028b09c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (c000000000510aa8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/quota/netlink.c (c000000000549940)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (c000000000677b58)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (c0000000006b59e4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (c000000000971564)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa9e94)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (c000000000bb8b74)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (c000000000c83610)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (c000000000c8cd7c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (c000000000c993d0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (c000000000cc75cc)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (c000000000cd40b0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (c000000000cece54)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (c000000000cfe170)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (c000000000d00348)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (c000000000d0d814)
Location: include/linux/skbuff.h:1048
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
In net/core/devlink.c (c000000000d292b4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (c000000000d38a1c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (c000000000d3d808)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (c000000000d468c8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (c000000000d4e5e8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (c000000000d50628)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (c000000000d5f1a4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (c000000000d659c8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (c000000000d6df50)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (c000000000d7e054)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (c000000000d88ce4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (c000000000d90e6c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (c000000000da27a8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (c000000000db43d0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (c000000000dbac90)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (c000000000dc5d94)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (c000000000dd20e0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/inet_fragment.c (c000000000dd9718)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (c000000000de0f10)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (c000000000dec42c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (c000000000e20710)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (c000000000e2aef0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (c000000000e3606c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (c000000000e45a78)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (c000000000e52754)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/tcp_ipv6.c (c000000000e68fc8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (c000000000e719c0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (c000000000e75b90)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (c000000000e77610)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (c000000000e9c16c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea26e8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea42a8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6678)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7cf8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (c000000000eac278)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_newmsg
```
```
In net/ncsi/ncsi-cmd.c (c000000000eb4588)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebd4b4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In lib/kobject_uevent.c (c000000000ecd820)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (ffffffe00015ef88)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffe00016e402)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (ffffffe0002b1292)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/quota/netlink.c (ffffffe0002d1790)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffe00038e62a)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_notify
```
```
In security/selinux/netlink.c (ffffffe0003af404)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/connector/connector.c (ffffffe0005742f2)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062ddce)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffe0006cfe90)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffe00073fd90)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffe000745976)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffe00074d700)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffe00076aa6c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffe000771fbc)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffe0007827a6)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffe00078d644)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffe00078eb52)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffe00079678a)
Location: include/linux/skbuff.h:1048
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
In net/core/devlink.c (ffffffe0007a66e8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffffffe0007ae7b2)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffe0007b13f4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffe0007b68aa)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffe0007bb6e2)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffe0007bcc80)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (ffffffe0007c59fc)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffe0007ca174)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf2d0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffe0007d9662)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0c0a)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffe0007e6820)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1ff0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffe0007fd8ba)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffe000801c8c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffe000808f52)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffe000810068)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/inet_fragment.c (ffffffe000814caa)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffe000819f8e)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffe000821448)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffe00084444c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffe00084afc0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffe000852914)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffe00085cdba)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffe000864548)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000873e7c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffe000879dc6)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffe00087c9fe)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffe00087dee2)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffe000895e2e)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a06c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089afc4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089c6e2)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d494)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffe0008a0bf8)
Location: include/linux/skbuff.h:1048
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffffffe0008a4c82)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab1ba)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In lib/kobject_uevent.c (ffffffe0008b4eca)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (ffffffff8116dd27)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8118d425)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (ffffffff8133e1d4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/quota/netlink.c (ffffffff813660ae)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff8143b2a3)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff81461c0e)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff815dc8e5)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff816ba164)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178e168)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffff8182c900)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffff818b4eaf)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff818bb529)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff818c4527)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff818e4220)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff818eddc4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff818ffeb9)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff8190ae03)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff8190c99a)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81916389)
Location: include/linux/skbuff.h:1048
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
In net/core/devlink.c (ffffffff81928446)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffffffff8193211f)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff81934d9b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff8193bd94)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff81941359)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff8194271d)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (ffffffff8194c8fb)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff81951a79)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81957e2d)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff81963776)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff8196bb2c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81972185)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197ecdb)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff8198b5f3)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff819903de)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff81997ff6)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff819a0b0d)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5ceb)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff819ab441)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff819b1e95)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff819d75a2)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff819df456)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819e7baf)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff819f3393)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff819fce81)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d777)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81a142e2)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81a17313)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a187f8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a325f0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a36337)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a37677)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a390c8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a0c1)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81a3d8d5)
Location: include/linux/skbuff.h:1048
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81a4252a)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a49025)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In lib/kobject_uevent.c (ffffffff81a509ab)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (ffffffff81160ec7)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81180545)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (ffffffff8132ee94)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/quota/netlink.c (ffffffff81356d4e)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff8142bd13)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff8145263e)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff815c7f25)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81697da4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff8170f794)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_host_post_fc_event
```
```
In drivers/net/vxlan.c (ffffffff817735d4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:__vxlan_fdb_notify
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81776f38)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffff817f3f90)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffff8186edff)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff81875469)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff8187e467)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff8189e060)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff818a7c04)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff818b9ce9)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff818c4b9e)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff818c675a)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff818d0139)
Location: include/linux/skbuff.h:1048
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
In net/core/devlink.c (ffffffff818e21f6)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffffffff818ebc1f)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff818ee89b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff818f5894)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff818fae49)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff818fc20d)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (ffffffff819063eb)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8190b569)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191191d)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff8191d266)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff8192561c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff8192bc55)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff8193879b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff819450b3)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff81949e9e)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff81951ab6)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a5cd)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f7ab)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff81964f01)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff8196e4c5)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81994362)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff8199c216)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a496f)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff819b0153)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff819b9c41)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca537)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff819d10a2)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff819d40d3)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff819d55b8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff819ef7e0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f2f57)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f4297)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f5ce8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6ce1)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff819fa4c5)
Location: include/linux/skbuff.h:1048
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819ff11a)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05c15)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In lib/kobject_uevent.c (ffffffff81a0daab)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (ffffffff8116baf7)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff8118b1f5)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (ffffffff8133bca4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/quota/netlink.c (ffffffff81363b7e)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff81437443)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff8145dcae)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff815e1a75)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff816e8634)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817be508)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffff8187bf30)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffff81905eaf)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff8190c529)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff81915527)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81935250)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff8193edf4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81950ee9)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff8195be33)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff8195d9ca)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff819673b9)
Location: include/linux/skbuff.h:1048
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
In net/core/devlink.c (ffffffff819795d6)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffffffff819832af)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff81985f2b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff8198cf24)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff819924e9)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff819938ad)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999d62)
Location: include/linux/skbuff.h:1048
Inline: True
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199c846)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfulnl_log_packet
  - net/netfilter/nfnetlink_log.c:nfulnl_log_packet
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b06d2)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_expect_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_stat_ct
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
```
```
In net/ipv4/route.c (ffffffff819b70cb)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff819bc249)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c25fd)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff819cdf46)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff819d62fc)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff819dc955)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e94ab)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff819f5dc7)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff819fac7e)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff81a02896)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0b3ad)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1058b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff81a15ce1)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81a1c735)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81a42022)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff81a49ed6)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a5262f)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81a5de13)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81a67901)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a781f7)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81a7ed62)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81a81d93)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a83278)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81a9e1a0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa21e7)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa3527)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa4f78)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa5f71)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81aa9785)
Location: include/linux/skbuff.h:1048
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aae3da)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4ed5)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In lib/kobject_uevent.c (ffffffff81abcd9b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
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
In kernel/audit.c (ffffffff811792b7)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/audit.c:audit_make_reply
```
```
In kernel/taskstats.c (ffffffff81198b65)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - kernel/taskstats.c:prepare_reply
```
```
In fs/io_uring.c (ffffffff8134ee54)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/quota/netlink.c (ffffffff8137722e)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In ipc/mqueue.c (ffffffff8144eb6b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In security/selinux/netlink.c (ffffffff8147544e)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_notify
```
```
In drivers/acpi/event.c (ffffffff815fb935)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
```
```
In drivers/connector/connector.c (ffffffff81702d34)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d8d38)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/thermal/thermal_core.c (ffffffff81897960)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
```
```
In net/core/sock.c (ffffffff81926edf)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
```
```
In net/core/skbuff.c (ffffffff8192d659)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:alloc_skb_for_msg
```
```
In net/core/net_namespace.c (ffffffff81936707)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81956960)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
```
```
In net/core/rtnetlink.c (ffffffff81960651)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
```
```
In net/core/sock_diag.c (ffffffff81972829)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/netpoll.c (ffffffff8197e213)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/fib_rules.c (ffffffff8197fc1a)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/fib_rules.c:notify_rule_change
```
```
In net/core/drop_monitor.c (ffffffff81989649)
Location: include/linux/skbuff.h:1048
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
In net/core/devlink.c (ffffffff8199bac6)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/core/devlink.c:devlink_nl_cmd_info_get_doit
  - net/core/devlink.c:devlink_nl_cmd_region_get_doit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_doit
  - net/core/devlink.c:devlink_nl_cmd_param_get_doit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_dpipe_send_and_alloc_skb
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_nl_cmd_get_doit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
```
In net/sched/sch_api.c (ffffffff819a57ff)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
```
In net/sched/cls_api.c (ffffffff819a8f2b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff819af7b4)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffff819b4fd9)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff819b639d)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
```
```
In net/ipv4/route.c (ffffffff819c094b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff819c5b59)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cbffd)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
```
```
In net/ipv4/tcp.c (ffffffff819d7ad6)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff819dff1c)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff819e65d5)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f320f)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
```
```
In net/ipv4/arp.c (ffffffff819fffc7)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/ipv4/devinet.c (ffffffff81a04fce)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
```
```
In net/ipv4/igmp.c (ffffffff81a0cdc6)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_semantics.c (ffffffff81a15b8d)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1addb)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv4/nexthop.c (ffffffff81a20721)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/ipmr.c (ffffffff81a276e7)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/ip6_output.c (ffffffff81a4dcb2)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/addrconf.c (ffffffff81a55e16)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e636)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81a6a223)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
```
```
In net/ipv6/ndisc.c (ffffffff81a73ef0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84967)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/datagram.c (ffffffff81a8b622)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6.c (ffffffff81a8e693)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
```
```
In net/ipv6/ip6mr.c (ffffffff81a8fb98)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/wireless/wext-core.c (ffffffff81aaa3a0)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aae557)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aaf947)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab12f8)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2311)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
```
```
In net/dcb/dcbnl.c (ffffffff81ab5af5)
Location: include/linux/skbuff.h:1048
Inline: True
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aba78a)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac1275)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In lib/kobject_uevent.c (ffffffff81ac921b)
Location: include/linux/skbuff.h:1048
Inline: True
Inline callers:
  - lib/kobject_uevent.c:alloc_uevent_skb
```
</details>
</li>
</ul>

## Differences
