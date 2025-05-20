# Function: <code>__alloc_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81706b50)
Location: net/core/skbuff.c:202
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:SyS_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:refill_skbs
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/fib_rules.c:notify_rule_change
  - net/sched/sch_api.c:tclass_notify
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tc_ctl_action
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/af_netlink.c:__netlink_alloc_skb
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
**Symbols:**

```
ffffffff81706b50-ffffffff81706d32: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176ce60)
Location: net/core/skbuff.c:203
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:SyS_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/sched/sch_api.c:tclass_notify
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff8176ce60-ffffffff8176d03a: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179a2e0)
Location: net/core/skbuff.c:203
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:SyS_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/sched/sch_api.c:tclass_notify
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff8179a2e0-ffffffff8179a4ba: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b9c70)
Location: net/core/skbuff.c:203
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/sched/sch_api.c:tclass_notify
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff817b9c70-ffffffff817b9e4d: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818325f0)
Location: net/core/skbuff.c:177
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/strparser/strparser.c:__strp_recv
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff818325f0-ffffffff818327c6: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187caf0)
Location: net/core/skbuff.c:177
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/strparser/strparser.c:__strp_recv
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff8187caf0-ffffffff8187ccc1: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189d750)
Location: net/core/skbuff.c:180
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/strparser/strparser.c:__strp_recv
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff8189d750-ffffffff8189d915: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e7fb0)
Location: net/core/skbuff.c:181
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__io_uring_register
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff818e7fb0-ffffffff818e817a: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81918e20)
Location: net/core/skbuff.c:181
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__io_uring_register
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff81918e20-ffffffff81918fea: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ebae0)
Location: net/core/skbuff.c:182
Inline: False
Direct callers:
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:alloc_uevent_skb
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-cmd.c:ncsi_alloc_command
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
**Symbols:**

```
ffffffff819ebae0-ffffffff819ebcda: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb980)
Location: net/core/skbuff.c:182
Inline: False
Direct callers:
  - kernel/audit.c:audit_buffer_alloc
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:alloc_uevent_skb
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_ifa_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-cmd.c:ncsi_alloc_command
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
**Symbols:**

```
ffffffff819eb980-ffffffff819ebb7a: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d0020)
Location: net/core/skbuff.c:394
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:alloc_uevent_skb
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
**Symbols:**

```
ffffffff819d0020-ffffffff819d01e4: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:396
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:alloc_uevent_skb
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
```
**Symbols:**

```
ffffffff81d3512c-ffffffff81d35140: __alloc_skb.cold (STB_LOCAL)
ffffffff81a80680-ffffffff81a8084d: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:394
Inline: False
Direct callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - lib/kobject_uevent.c:alloc_uevent_skb
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/xen-netfront.c:bounce_skb
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mctp/device.c:mctp_addr_notify
  - net/mctp/route.c:mctp_do_fragment_route
```
**Symbols:**

```
ffffffff81f01689-ffffffff81f0169e: __alloc_skb.cold (STB_LOCAL)
ffffffff81bf4dc0-ffffffff81bf4f9b: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:532
Inline: False
Direct callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - io_uring/rsrc.c:__io_scm_file_account
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mctp/device.c:mctp_addr_notify
  - net/mctp/route.c:mctp_do_fragment_route
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff820aac05-ffffffff820aac19: __alloc_skb.cold (STB_LOCAL)
ffffffff81da4230-ffffffff81da43f2: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:621
Inline: False
Direct callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - io_uring/rsrc.c:__io_scm_file_account
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
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
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
  - net/devlink/dev.c:devlink_nl_cmd_selftests_get_doit
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:devlink_nl_cmd_info_get_doit
  - net/devlink/dev.c:devlink_nl_cmd_eswitch_get_doit
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_get_doit
  - net/devlink/dev.c:devlink_notify
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_get_doit
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mctp/device.c:mctp_addr_notify
  - net/mctp/route.c:mctp_do_fragment_route
  - net/handshake/netlink.c:handshake_genl_notify
  - net/handshake/tlshd.c:tls_handshake_accept
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff8212c118-ffffffff8212c12d: __alloc_skb.cold (STB_LOCAL)
ffffffff81e12ea0-ffffffff81e13050: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:622
Inline: False
Direct callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/regulator/event.c:reg_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_id_get_doit
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_napi_get_doit
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
  - net/core/netdev-genl.c:netdev_genl_dev_notify
  - net/core/page_pool_user.c:netdev_nl_page_pool_event
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_do
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_del_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/devlink/netlink.c:devlink_nl_msg_reply_and_new
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
  - net/devlink/dev.c:devlink_nl_selftests_get_doit
  - net/devlink/dev.c:__devlink_compat_running_version
  - net/devlink/dev.c:devlink_nl_info_get_doit
  - net/devlink/dev.c:devlink_nl_eswitch_get_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_get_doit
  - net/devlink/port.c:devlink_nl_port_new_doit
  - net/devlink/port.c:devlink_nl_port_get_doit
  - net/devlink/port.c:devlink_port_notify
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_doit
  - net/devlink/sb.c:devlink_nl_sb_port_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_pool_get_doit
  - net/devlink/sb.c:devlink_nl_sb_get_doit
  - net/devlink/dpipe.c:devlink_dpipe_send_and_alloc_skb
  - net/devlink/param.c:devlink_nl_param_get_doit
  - net/devlink/region.c:devlink_nl_region_get_doit
  - net/devlink/region.c:devlink_nl_region_notify_build
  - net/devlink/health.c:devlink_nl_health_reporter_get_doit
  - net/devlink/trap.c:devlink_nl_trap_policer_get_doit
  - net/devlink/trap.c:devlink_nl_trap_group_get_doit
  - net/devlink/trap.c:devlink_nl_trap_get_doit
  - net/devlink/rate.c:devlink_nl_rate_get_doit
  - net/devlink/rate.c:devlink_rate_notify
  - net/devlink/linecard.c:devlink_nl_linecard_get_doit
  - net/devlink/linecard.c:devlink_linecard_notify
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
  - net/mctp/device.c:mctp_addr_notify
  - net/mctp/route.c:mctp_do_fragment_route
  - net/handshake/netlink.c:handshake_genl_notify
  - net/handshake/tlshd.c:tls_handshake_accept
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff8220ddf8-ffffffff8220de0d: __alloc_skb.cold (STB_LOCAL)
ffffffff81ed0060-ffffffff81ed0210: __alloc_skb (STB_GLOBAL)
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
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb1f30)
Location: net/core/skbuff.c:181
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffff800010bb1f30-ffff800010bb20d0: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccfe70)
Location: net/core/skbuff.c:181
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
c0ccfe70-c0ccffec: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c89890)
Location: net/core/skbuff.c:181
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/dcb/dcbnl.c:dcbnl_newmsg
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
c000000000c89890-c000000000c89ab8: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000743634)
Location: net/core/skbuff.c:181
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:__se_sys_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffe000743634-ffffffe000743796: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b8e20)
Location: net/core/skbuff.c:181
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__io_uring_register
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff818b8e20-ffffffff818b8fea: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81872d70)
Location: net/core/skbuff.c:181
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__io_uring_register
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/scsi/scsi_transport_fc.c:fc_host_post_fc_event
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:__vxlan_fdb_notify
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff81872d70-ffffffff81872f3a: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81909e20)
Location: net/core/skbuff.c:181
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__io_uring_register
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netfilter/nfnetlink_log.c:nfulnl_log_packet
  - net/netfilter/nfnetlink_log.c:nfulnl_log_packet
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_expect_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_stat_ct
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff81909e20-ffffffff81909fea: __alloc_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *__alloc_skb(unsigned int size, gfp_t gfp_mask, int flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192af20)
Location: net/core/skbuff.c:181
Inline: False
Direct callers:
  - kernel/audit.c:audit_make_reply
  - kernel/taskstats.c:prepare_reply
  - fs/io_uring.c:__io_uring_register
  - fs/quota/netlink.c:quota_send_warning
  - ipc/mqueue.c:do_mq_notify
  - security/selinux/netlink.c:selnl_notify
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:alloc_skb_for_msg
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:refill_skbs
  - net/core/fib_rules.c:notify_rule_change
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_config_get
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:reset_per_cpu_data
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
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/genetlink.c:genl_ctrl_event
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/arp.c:arp_create
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_list
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
  - lib/kobject_uevent.c:alloc_uevent_skb
```
**Symbols:**

```
ffffffff8192af20-ffffffff8192b0ea: __alloc_skb (STB_GLOBAL)
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
