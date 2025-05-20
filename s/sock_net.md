# Function: <code>sock_net</code>

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
In kernel/audit.c (ffffffff81121d06)
Location: include/net/sock.h:2211
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81125363)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff813eca46)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
```
```
In drivers/net/tun.c (ffffffff815f0061)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff816fbd99)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/socket.c:sock_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:SyS_socketcall
```
```
In net/core/sock.c (ffffffff817039a5)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/datagram.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8170fac3)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff8172682c)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8172aa86)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
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
In net/core/sock_diag.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/core/fib_rules.c (ffffffff8173a15c)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff817436c7)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (ffffffff81746190)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff81748c68)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff8174a1a6)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_bind
```
```
In net/netlink/genetlink.c (ffffffff8174f4fb)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
```
In net/ipv4/route.c (ffffffff81757125)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_input.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175e266)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762199)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8176356b)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81763b96)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp.c (ffffffff817687b4)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8176b321)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81775875)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8177a396)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c48c)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817817e9)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff81783cc1)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81784cf4)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81786176)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817904b3)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/af_inet.c (ffffffff81792fc0)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_ioctl
```
```
In net/ipv4/igmp.c (ffffffff81796ec8)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_drop_socket
```
```
In net/ipv4/fib_frontend.c (ffffffff81799c09)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
```
```
In net/ipv4/ping.c (ffffffff817a2811)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/fib_rules.c (ffffffff817a6bfc)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff817a8b23)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/ipv4/syncookies.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/unix/af_unix.c (ffffffff817c0586)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/af_inet6.c (ffffffff817c2bac)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:inet6_ioctl
```
```
In net/ipv6/anycast.c (ffffffff817c3df7)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_close
```
```
In net/ipv6/ip6_output.c (ffffffff817c4c5b)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_send_skb
```
```
In net/ipv6/addrconf.c (ffffffff817cb9ac)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
```
In net/ipv6/addrlabel.c (ffffffff817d263c)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff817d402c)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/ip6_fib.c (ffffffff817da459)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817dceb8)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/ipv6/udp.c (ffffffff817e3614)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff817e520d)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff817e7a69)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff817ebf7b)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_close
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817eeedd)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ping.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f69e5)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/ip6mr.c (ffffffff817f93e9)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
```
```
In net/ipv6/fib6_rules.c (ffffffff817fe1f9)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (0)
Location: include/net/sock.h:2211
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81802339)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81805847)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81813d9b)
Location: include/net/sock.h:2211
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
In kernel/audit.c (ffffffff81129c46)
Location: include/net/sock.h:2193
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8112d401)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81432d04)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
```
```
In drivers/net/tun.c (ffffffff8164f491)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff817633d2)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:SyS_socketcall
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff81768868)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/net_namespace.c (ffffffff817773f3)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/dev.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/core/neighbour.c (ffffffff81790ae1)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8179a034)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
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
In net/core/sock_diag.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/core/fib_rules.c (ffffffff817a6f7c)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff817b0567)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff817b31a0)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff817b4b1c)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff817b882e)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netlink/genetlink.c (ffffffff817bc1c9)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff817c34d9)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_input.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817cb8a5)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cc8a6)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cf3c3)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0c81)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff817d1dd2)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff817dbe42)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff817e69a4)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv4/tcp_timer.c (ffffffff817e6bf8)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e8306)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817eeca9)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff817f1278)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff817f22f9)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f5434)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817fda8c)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff81801276)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff81807443)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81807f42)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff8181073d)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/fib_rules.c (ffffffff818148fc)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff818177a3)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/syncookies.c (ffffffff81819187)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8182e852)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81830056)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81831338)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81835387)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff818389dc)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff818408d3)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81842621)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ip6_fib.c (ffffffff81847f89)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184aee8)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81851d14)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81854518)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81855efa)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8185b390)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185d7c8)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ping.c (0)
Location: include/net/sock.h:2193
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81865b55)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/ip6mr.c (ffffffff81868c29)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff8186db5a)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff8186ee44)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818735e9)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff818771d9)
Location: include/net/sock.h:2193
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
```
In net/dcb/dcbnl.c (ffffffff81886c7b)
Location: include/net/sock.h:2193
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
In kernel/audit.c (ffffffff81133966)
Location: include/net/sock.h:2260
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81137131)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff8144ef74)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
```
```
In drivers/net/tun.c (ffffffff816817a1)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff817904c2)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:SyS_socketcall
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff81796c99)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/net_namespace.c (ffffffff817a43f1)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/dev.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In net/core/neighbour.c (ffffffff817be391)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff817c7dd4)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
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
In net/core/sock_diag.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In net/core/fib_rules.c (ffffffff817d5abc)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff817dfca7)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff817e2a20)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff817e43dc)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff817e82de)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netlink/genetlink.c (ffffffff817eb922)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff817f2ad0)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_input.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817fb505)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fc5a6)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ff1b3)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800b12)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff81801d37)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff8180bf16)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff818170e4)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv4/tcp_timer.c (ffffffff81817338)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181a9d3)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f6b9)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff81822314)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818230da)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81826516)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8182e9ec)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff81832086)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff818384d3)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81839012)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81841c3d)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/fib_rules.c (ffffffff8184609b)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81849013)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/syncookies.c (ffffffff8184a9fb)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In net/unix/af_unix.c (ffffffff818602d2)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81861ad6)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81862da8)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81866eb7)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff8186a50c)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81872553)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81874371)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ip6_fib.c (ffffffff81879dc9)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187cd88)
Location: include/net/sock.h:2260
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81883ad4)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff8188623a)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81887d4f)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8188d225)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188f817)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ping.c (0)
Location: include/net/sock.h:2260
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff818942a2)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81898225)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/seg6.c (ffffffff81899783)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff8189ba79)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff818a093a)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff818a1d94)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7c59)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff818ac234)
Location: include/net/sock.h:2260
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
```
In net/dcb/dcbnl.c (ffffffff818bb4eb)
Location: include/net/sock.h:2260
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
In kernel/audit.c (ffffffff81136a98)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff8113840b)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (0)
Location: include/net/sock.h:2287
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2287
Inline: True
```
```
In drivers/net/tun.c (ffffffff816965d6)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff817af7d4)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff817b5084)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/net_namespace.c (ffffffff817c2561)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff817dc6a5)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff817e6643)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
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
In net/core/filter.c (ffffffff817ea143)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/sock_diag.c (0)
Location: include/net/sock.h:2287
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/net/sock.h:2287
Inline: True
```
```
In net/core/fib_rules.c (ffffffff817f4f49)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/sched/sch_api.c (ffffffff817ff167)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81802316)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff81803e1c)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff81808375)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
```
```
In net/netlink/genetlink.c (ffffffff8180b8bb)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff81813385)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_input.c (0)
Location: include/net/sock.h:2287
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8181b8e5)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181c97c)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f3fb)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/sock.h:2287
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820702)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff8182336e)
Location: include/net/sock.h:2287
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8182c0c1)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81837544)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff818376de)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b1b0)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/sock.h:2287
Inline: True
```
```
In net/ipv4/tcp_cong.c (0)
Location: include/net/sock.h:2287
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8184005c)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/net/sock.h:2287
Inline: True
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/net/sock.h:2287
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff81842f84)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81843c13)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81846c07)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (0)
Location: include/net/sock.h:2287
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8184f449)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff81853656)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff81859923)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff8185a532)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff8186351d)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/fib_rules.c (ffffffff81867c65)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff8186a8f9)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/syncookies.c (ffffffff8186e3cb)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/net/sock.h:2287
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81884a13)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/af_inet6.c (ffffffff818861f6)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81887578)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff8188b667)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff8188ea79)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff818972c7)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff8189916c)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ip6_fib.c (ffffffff818a0303)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a288f)
Location: include/net/sock.h:2287
Inline: True
```
```
In net/ipv6/udp.c (ffffffff818a9d84)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff818ac987)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff818ae3ac)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff818b27b7)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b5e8d)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (0)
Location: include/net/sock.h:2287
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff818bb78b)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818be5b0)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/seg6.c (ffffffff818bf983)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff818c1e29)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff818c6f55)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff818c83a6)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce4f1)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff818d230e)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
```
In net/dcb/dcbnl.c (ffffffff818e1ee1)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In lib/kobject_uevent.c (ffffffff818ef1a6)
Location: include/net/sock.h:2287
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
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
In kernel/audit.c (ffffffff8114342f)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff8114511b)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (0)
Location: include/net/sock.h:2301
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2301
Inline: True
```
```
In drivers/net/tun.c (ffffffff817013cd)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff81827924)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff8182d4c0)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/net_namespace.c (ffffffff8183bfb1)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff81857285)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8185ba73)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
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
In net/core/filter.c (ffffffff818657d3)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/sock_diag.c (0)
Location: include/net/sock.h:2301
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/net/sock.h:2301
Inline: True
```
```
In net/core/fib_rules.c (ffffffff818707a9)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (0)
Location: include/net/sock.h:2301
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8187cdf7)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81880734)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_ctl_tfilter
```
```
In net/sched/act_api.c (ffffffff818823f0)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff818871d5)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
```
```
In net/netlink/genetlink.c (ffffffff8188a84b)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff818929d5)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_input.c (0)
Location: include/net/sock.h:2301
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8189a81b)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189b8bc)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189e35b)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/sock.h:2301
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189f6d2)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff818a635a)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff818aaf51)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff818b6c04)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff818b6e08)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b87d4)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/sock.h:2301
Inline: True
```
```
In net/ipv4/tcp_cong.c (ffffffff818be44c)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf3fc)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0edc)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/net/sock.h:2301
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff818c28ea)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818c3533)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818c663a)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (0)
Location: include/net/sock.h:2301
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff818cf079)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff818d34b6)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff818d9823)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff818da452)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff818e365d)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/fib_rules.c (ffffffff818e7d56)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff818eb089)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/syncookies.c (ffffffff818eed78)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/net/sock.h:2301
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f972f)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/unix/af_unix.c (ffffffff81905bf3)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819073f6)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff819087a8)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff8190c907)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff819100c9)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81917f67)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff8191d74c)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
```
```
In net/ipv6/ip6_fib.c (ffffffff81922353)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8192520f)
Location: include/net/sock.h:2301
Inline: True
```
```
In net/ipv6/udp.c (ffffffff8192c784)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff8192f1e7)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff8193104e)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81935517)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938c2c)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (0)
Location: include/net/sock.h:2301
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff8193e845)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819416f0)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/seg6.c (ffffffff81942a53)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff81945769)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff8194a400)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff8194b95c)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81953378)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81957243)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
```
```
In net/dcb/dcbnl.c (ffffffff81967c81)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In lib/kobject_uevent.c (ffffffff81975486)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
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
In kernel/audit.c (ffffffff81151f1e)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff81153aa3)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (ffffffff813fec3d)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2308
Inline: True
```
```
In drivers/net/tun.c (ffffffff817404a1)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff81871f59)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff81875031)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff818866c9)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/neighbour.c (ffffffff818a30c5)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818a73e9)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:get_target_net
```
```
In net/core/filter.c (ffffffff818b3ca2)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_uid
```
```
In net/core/sock_diag.c (ffffffff818b8af5)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/core/net-sysfs.c (ffffffff818bb125)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff818c1fb5)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff818c39e3)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/sched/sch_api.c (ffffffff818cf659)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d34cf)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff818d5f00)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff818da368)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_undo_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff818dde84)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff818e698a)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff818eed17)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff818ef84a)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2dfe)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f32d5)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f40ea)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff818fb446)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819004c1)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff8190c455)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c76b)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190eef8)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819132c9)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819146b3)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914fd5)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81916ad0)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
```
```
In net/ipv4/tcp_recovery.c (ffffffff819171e5)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (ffffffff81918555)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81918d96)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff8191c68c)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:compute_score
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff819237ae)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81925e05)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff819298af)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff81930245)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81930eb1)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81939ef5)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/fib_rules.c (ffffffff8193e955)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81941877)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff819441e3)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff8194544e)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff819460d0)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/xfrm/xfrm_policy.c (ffffffff81950185)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/unix/af_unix.c (ffffffff81958be5)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffff8195dfca)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff8195f9a1)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff8196018a)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff819674c5)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8196f797)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff8197252c)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
```
```
In net/ipv6/ip6_fib.c (ffffffff8197a6df)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197c9ab)
Location: include/net/sock.h:2308
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81983e6a)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff8198795f)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81989cdd)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8198e680)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819940a6)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_stream_memory_free
```
```
In net/ipv6/ping.c (ffffffff81995aee)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81997790)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/datagram.c (ffffffff81998587)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8199a82a)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/seg6.c (ffffffff8199b975)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff819a0507)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff819a3481)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff819a4a69)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819acdb6)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff819b165a)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dcb/dcbnl.c (ffffffff819c14b1)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819ca88e)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff819cbbeb)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In lib/kobject_uevent.c (ffffffff819d19a0)
Location: include/net/sock.h:2308
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff8115ebda)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff81160833)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (ffffffff8141ab04)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2439
Inline: True
```
```
In drivers/net/tun.c (ffffffff817644ce)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff81891aa9)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff818958fe)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff818a7a0c)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff818aa0e3)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff818c6b51)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818cb229)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff818d8f35)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff818df745)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/core/net-sysfs.c (ffffffff818e2205)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff818eae01)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff818ec907)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/sched/sch_api.c (ffffffff818fa549)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff818ff90f)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81902700)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff81906da8)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_undo_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff8190a844)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff81913843)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8191c4cf)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191d008)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff8192088e)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920df5)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921bfa)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff81929392)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff8192e621)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff8193a735)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff8193aad5)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193d328)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941a81)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81942e63)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943995)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81945280)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
```
```
In net/ipv4/tcp_recovery.c (ffffffff819459f5)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (ffffffff81946cd5)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819475e6)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff8194ac2c)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff8195259e)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81954dea)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff819589df)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff8195f725)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff819607b1)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81969d54)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/fib_rules.c (ffffffff8196e805)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff8197110c)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff81974555)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff819757ff)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff81976270)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/xfrm/xfrm_policy.c (ffffffff81983835)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/unix/af_unix.c (ffffffff8198d795)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffff81992b0a)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81994601)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81994f6a)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff8199cad5)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a53aa)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819a80a0)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff819afeb8)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b29bc)
Location: include/net/sock.h:2439
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819ba3ae)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff819be293)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff819c0593)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c4f30)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca9c8)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_stream_memory_free
```
```
In net/ipv6/ping.c (ffffffff819cc3fa)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff819ce060)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/datagram.c (ffffffff819ce8cc)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d117a)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/seg6.c (ffffffff819d2355)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff819d2f76)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff819d9f91)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff819db591)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3778)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff819e8a43)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dcb/dcbnl.c (ffffffff819f8a01)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a033c9)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81a04e3b)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In lib/kobject_uevent.c (ffffffff81a0afc0)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff8116b074)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff8116ceb3)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (ffffffff814485e6)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2452
Inline: True
```
```
In drivers/net/tun.c (ffffffff817a2241)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff818dba8a)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff818dfe2b)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff818f36de)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff818f5b46)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff81912c91)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81917c69)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff819248ed)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff8192dd95)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/net-sysfs.c (ffffffff819317d5)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff8193a8a1)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff8193caac)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff819431c7)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff819518fe)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
```
```
In net/sched/sch_api.c (ffffffff81959df9)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff8196017f)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81963960)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff81968048)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_undo_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff8196bc41)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff81975e23)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8197e80a)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197f4e5)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff819831d7)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819837be)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819845df)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff8198c2d0)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81991c04)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff8199ea85)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff8199ee7c)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a1758)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a6079)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819a6dc5)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a8325)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a98a0)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
```
```
In net/ipv4/tcp_recovery.c (ffffffff819a9ff5)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (ffffffff819ab355)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819abc79)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff819af279)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff819b6e66)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff819b8d61)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff819bd513)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff819c45b5)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff819c5335)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff819d0a14)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff819d462d)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff819d8005)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff819da88c)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff819de085)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff819df31d)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff819dfdf4)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ed415)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/unix/af_unix.c (ffffffff819f8eb8)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffff819fe42a)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81a00105)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a00a0a)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff81a08cb5)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a11848)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a1518c)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1e04c)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a20e9c)
Location: include/net/sock.h:2452
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a294ef)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81a2d56e)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a2eaf6)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81a33db0)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a395f6)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_stream_memory_free
```
```
In net/ipv6/ping.c (ffffffff81a3aeec)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a3cc71)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/datagram.c (ffffffff81a3d570)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a4002f)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/seg6.c (ffffffff81a41175)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff81a41dea)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff81a48c61)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff81a4a201)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a52484)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81a58d82)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dcb/dcbnl.c (ffffffff81a67f51)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a72649)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81a7433d)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In lib/kobject_uevent.c (ffffffff81a7a9a2)
Location: include/net/sock.h:2452
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff81176f3f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff81178d53)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (ffffffff81462176)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2473
Inline: True
```
```
In drivers/net/tun.c (ffffffff817c43d1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff8190e66a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff81911fdb)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff8192568e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff81927a54)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff819452f1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8194a289)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81956d3c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff81960025)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/net-sysfs.c (ffffffff81964315)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff8196d761)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff8196f93c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff8197813b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff8198360b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
```
```
In net/sched/sch_api.c (ffffffff81990299)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff8199725f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff8199a4e0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff8199eae8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_undo_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff819a25f1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff819ac833)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819b51aa)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b5a25)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b9a47)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819b9fae)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bad8f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff819c2c20)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819c880a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff819d5595)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff819d591c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d8408)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dd049)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819dda95)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff819deff5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e0560)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819e0cb5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (ffffffff819e2025)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819e2929)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff819e5f89)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff819edb66)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff819efa71)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff819f4123)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff819fb155)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff819fbed5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81a07564)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81a0b19d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff81a0eaf5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81a1170c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff81a15125)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff81a163b7)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a16de4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a24425)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/unix/af_unix.c (ffffffff81a2fb08)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffff81a358d3)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81a36ce5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a375dd)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff81a3f3c5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a48468)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a4bd5c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54cac)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a5790c)
Location: include/net/sock.h:2473
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6004b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81a640d4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a65646)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81a6a900)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70186)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_stream_memory_free
```
```
In net/ipv6/ping.c (ffffffff81a71b6c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a738ed)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/datagram.c (ffffffff81a741d0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a76c9f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a77318)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffff81a77df5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff81a78a4a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7f851)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff81a80dc6)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a89094)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81a8eecf)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dcb/dcbnl.c (ffffffff81a9e8b1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa8e09)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81aab4cd)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In lib/kobject_uevent.c (ffffffff81ab1d02)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff811898bf)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff8118bfba)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (ffffffff814b568e)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2525
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff815ec122)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:uevent_net_broadcast_tagged
```
```
In drivers/net/tun.c (ffffffff8188fe14)
Location: include/net/sock.h:2525
Inline: True
```
```
In net/socket.c (ffffffff819e08d2)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff819e3f82)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff819f89da)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff819fbc84)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff81a12455)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:pneigh_dump_table
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a1a899)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81a2d0cc)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff81a33425)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/net-sysfs.c (ffffffff81a37225)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff81a40a11)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff81a43827)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff81a4cc59)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff81a5f7db)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_netns_get
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
```
```
In net/sched/sch_api.c (ffffffff81a67dd9)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a6f59f)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff81a74e8d)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff81a76ba3)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
```
```
In net/netlink/genetlink.c (0)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ethtool/netlink.c (ffffffff81a86164)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ipv4/route.c (ffffffff81a96fb5)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81a9f409)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9ff8a)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_setsockopt
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa44a5)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4a2e)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa564f)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp.c (ffffffff81aa94fe)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81ab3d28)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_dsack_extend
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_update_pacing_rate
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
  - net/ipv4/tcp_input.c:tcp_measure_rcv_mss
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1ed5)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_tso_should_defer
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2b44)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac43b8)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9e8b)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81acad75)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbe05)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acdb30)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ace2a5)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/datagram.c (ffffffff81acf325)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81acff29)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ad2609)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_demux_lookup
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_reuseport_add_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81adb966)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81addeb1)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff81ae3694)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff81ae9a85)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeaac5)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81af6dc5)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81afbd44)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff81aff8b5)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81b049a5)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff81b06ae5)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff81b073c9)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff81b07ed9)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b162d5)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/xfrm/espintcp.c (ffffffff81b22974)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:handle_esp
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81b23b8b)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a7af)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_compat_routing_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81b2beb5)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b2cb04)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff81b35045)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f10c)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b46de6)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4c6ee)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4fb4d)
Location: include/net/sock.h:2525
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b58e4a)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_demux_lookup
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81b5cb48)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81b5eb12)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81b6383e)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69d96)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_stream_memory_free
```
```
In net/ipv6/ping.c (ffffffff81b6b45f)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b6bfea)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
```
```
In net/ipv6/datagram.c (ffffffff81b6e4d0)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70f2a)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b715a6)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffff81b72075)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff81b733da)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff81b7ba40)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b841c4)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81b85a4b)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mc_drop
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:init_prb_bdqc
```
```
In net/dcb/dcbnl.c (ffffffff81b99692)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba559a)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81ba6aed)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bad9e5)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_worker
```
```
In net/mptcp/subflow.c (ffffffff81bafb6f)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_init_req
  - net/mptcp/subflow.c:subflow_init_req
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb3855)
Location: include/net/sock.h:2525
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
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
In kernel/audit.c (ffffffff81186c99)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff811891ca)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (ffffffff814d3354)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2546
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81610902)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:uevent_net_broadcast_tagged
```
```
In drivers/net/tun.c (0)
Location: include/net/sock.h:2546
Inline: True
```
```
In net/socket.c (ffffffff819e0122)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff819e38c2)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff819f865a)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff819fb8b9)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff81a127e5)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:pneigh_dump_table
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a1aabd)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81a2ee55)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff81a35795)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/net-sysfs.c (ffffffff81a39635)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff81a43ed1)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff81a47427)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff81a52919)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff81a67fcb)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_netns_get
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
```
```
In net/sched/sch_api.c (ffffffff81a704d9)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a77f9f)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff81a7f923)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
```
```
In net/netlink/genetlink.c (ffffffff81a85502)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ethtool/netlink.c (ffffffff81a8fa3a)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81a976a5)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
```
```
In net/ipv4/route.c (ffffffff81aa10c9)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81aa9349)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaa8d1)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aaeaf5)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_lookup_by_sk
  - net/ipv4/inet_hashtables.c:inet_ehash_lookup_by_sk
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf08e)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafc5f)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp.c (ffffffff81ab381e)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81abe680)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_dsack_extend
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_mark_skb_lost
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_update_pacing_rate
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
  - net/ipv4/tcp_input.c:tcp_measure_rcv_mss
```
```
In net/ipv4/tcp_output.c (ffffffff81acd945)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_tso_should_defer
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace574)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81acf3f1)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5dcf)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad6d25)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7dc5)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad9b90)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ada2b5)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/datagram.c (ffffffff81adb32a)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81adbea9)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ae41fd)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_demux_lookup
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_reuseport_add_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81ae842a)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81aeac91)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff81af024b)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff81af6925)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81af7965)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81b03c55)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81b095d4)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff81b0d935)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81b12b15)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff81b14cea)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff81b15797)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff81b162b9)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b24755)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/xfrm/espintcp.c (ffffffff81b31624)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:handle_esp
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81b3255b)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffff81b39134)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_compat_routing_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81b3a8d5)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b514)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff81b43c65)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b4db8c)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b559e6)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5b32e)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5fdcc)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/udp.c (ffffffff81b67487)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_demux_lookup
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81b6b391)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81b6d29a)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81b71fee)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78876)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81b79eed)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b7aa5a)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
```
```
In net/ipv6/datagram.c (ffffffff81b7cf77)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7f541)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_renew
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b8021b)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffff81b80dd5)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff81b8210a)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff81b8aa80)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93a2b)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81b9545b)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mc_drop
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:init_prb_bdqc
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb4a6a)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81bb5d1d)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bbd725)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81bc3549)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_subflow_discard_data
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81bc54c7)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
```
```
In net/mptcp/token.c (ffffffff81bc5a94)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7ae5)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_subflow_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mptcp/syncookies.c (ffffffff81bc955b)
Location: include/net/sock.h:2546
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
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
In kernel/audit.c (ffffffff81187c10)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff81189f8f)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (ffffffff814d98b4)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2582
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff815f3fc2)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
```
In drivers/net/tun.c (ffffffff818809bd)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff819c5fd2)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff819c9942)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff819dee8a)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff819e19c5)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff819fb116)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81a019fd)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81a16405)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff81a1c8e5)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/net-sysfs.c (ffffffff81a20925)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff81a28d21)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff81a2c0d7)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff81a38093)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff81a430cb)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
```
```
In net/sched/sch_api.c (ffffffff81a58ddc)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a60dbf)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff81a688e3)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff81a6ece2)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_rcv_msg
```
```
In net/ethtool/netlink.c (ffffffff81a7916a)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81a81105)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
```
```
In net/ipv4/route.c (ffffffff81a8c04b)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81a94508)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a95ea1)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99d35)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a39c)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9af6f)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp.c (ffffffff81a9ecfe)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81aaa9dd)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_dsack_extend
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_mark_skb_lost
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_update_pacing_rate
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8b05)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_tso_should_defer
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab9704)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81aba541)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0e33)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac1dc5)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2f35)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4bee)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ac5315)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/datagram.c (ffffffff81ac638b)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ac6d49)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ac9db2)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81ad36ba)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81ad63d1)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff81ada666)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff81ae2075)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae3085)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81aef8b4)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81af8baa)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff81afb725)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81afc298)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff81b02aea)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff81b035a9)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff81b0408e)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12375)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/xfrm/espintcp.c (ffffffff81b1f337)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81b2008b)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffff81b26e18)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81b285b5)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b28c92)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff81b318c5)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b61c)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81b435f6)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff81b497de)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4e0ac)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/udp.c (ffffffff81b55661)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81b596e1)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81b5b5d1)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81b6175a)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66b82)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81b68a1e)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b694a4)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
```
```
In net/ipv6/datagram.c (ffffffff81b6ba56)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6e8d9)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b6ee1f)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffff81b6f925)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff81b70d2a)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff81b798ee)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82b3b)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81b8a572)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba3a4a)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81ba4cfd)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bab8bd)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81bb3bb9)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81bb5d13)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
```
```
In net/mptcp/token.c (ffffffff81bb6613)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbb924)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mptcp/sockopt.c (ffffffff81bbbceb)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
```
In net/mptcp/syncookies.c (ffffffff81bbce93)
Location: include/net/sock.h:2582
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
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
In kernel/audit.c (ffffffff811b0070)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff811b29cf)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/cgroup.c (ffffffff81272645)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_get_netns_cookie_sockopt
```
```
In security/selinux/hooks.c (ffffffff815327af)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2641
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81661332)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
```
In drivers/net/tun.c (ffffffff819122cd)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff81a75542)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff81a78d18)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff81a8f25d)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff81a91ec1)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff81aacf69)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81ab3dfd)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81accc99)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_get_netns_cookie_sk_msg
  - net/core/filter.c:bpf_get_netns_cookie_sock_ops
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff81ad0165)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/sock_reuseport.c (ffffffff81ad1c03)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
```
```
In net/core/net-sysfs.c (ffffffff81ad4d65)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff81addae1)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff81ae1167)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff81aeded3)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff81af954c)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
```
```
In net/sched/sch_api.c (ffffffff81b11e1c)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b19fcf)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff81b21d33)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff81b28722)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_rcv_msg
```
```
In net/ethtool/netlink.c (ffffffff81b33415)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81b3ae55)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
```
```
In net/ipv4/route.c (ffffffff81b46fd7)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81b4f988)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b51301)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b551a5)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b5580c)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b563df)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp.c (ffffffff81b5ac9e)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81b66dcd)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_dsack_extend
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_mark_skb_lost
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_update_pacing_rate
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff81b75d25)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_tso_segs
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76b39)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b77887)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e954)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81b7fae5)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b80b15)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b8339e)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81b83b25)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/datagram.c (ffffffff81b84b9b)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81b85569)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81b88642)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_sock
  - net/ipv4/udp.c:udp_read_sock
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81b9230a)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81b950f8)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff81b998d6)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff81ba1815)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba26b5)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81baf8c4)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81bb72da)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff81bbcbb5)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81bc1d45)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc4c84)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff81bc5839)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff81bc63d9)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd6215)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/xfrm/espintcp.c (ffffffff81be3f20)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/unix/af_unix.c (ffffffff81be4f15)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffff81bed104)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81bee54e)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81beeb82)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff81bf7965)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81c01e3c)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81c0a156)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff81c10d8e)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c153e5)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/udp.c (ffffffff81c1e13a)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81c21353)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81c22ce4)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81c291c4)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e737)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81c306e8)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81c30ed4)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
```
```
In net/ipv6/datagram.c (ffffffff81c338b6)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c36942)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81c36ea4)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffff81c379d5)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ioam6.c (ffffffff81c38b25)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpns_start
```
```
In net/ipv6/ip6mr.c (ffffffff81c3b726)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff81c44598)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4ec0b)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81c56689)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c7104a)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81c7288d)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81c79e1e)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81c8230a)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
  - net/mptcp/subflow.c:validate_data_csum
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81c84b75)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_syn_options
  - net/mptcp/options.c:mptcp_syn_options
```
```
In net/mptcp/token.c (ffffffff81c85623)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm.c (ffffffff81c86c5e)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b564)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mptcp/sockopt.c (ffffffff81c8b875)
Location: include/net/sock.h:2641
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
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
In kernel/audit.c (ffffffff811e2262)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff811e4d2f)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/cgroup.c (ffffffff812c19c5)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_get_netns_cookie_sockopt
```
```
In security/selinux/hooks.c (ffffffff815c9bac)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:616
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff8177b0d0)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
```
In drivers/net/tun.c (ffffffff81a65262)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff81be835f)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff81bec7a0)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff81c04fed)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff81c07df6)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff81c26158)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81c2d4cd)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81c49979)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_get_netns_cookie_sk_msg
  - net/core/filter.c:bpf_get_netns_cookie_sock_ops
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff81c4d9c5)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/sock_reuseport.c (ffffffff81c4f4a4)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
```
```
In net/core/net-sysfs.c (ffffffff81c54fa5)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff81c5e6a1)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff81c654a0)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff81c70cec)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff81c86d4d)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
```
```
In net/sched/sch_api.c (ffffffff81c990ec)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81c9f07c)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff81caa5e3)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff81cb1952)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_rcv_msg
```
```
In net/ethtool/netlink.c (ffffffff81cbe608)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81cc6df5)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
```
```
In net/ipv4/route.c (ffffffff81cd4085)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81cdd407)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cde23c)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2d55)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3506)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4521)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff81ce9486)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81cf5e3a)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_dsack_extend
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_mark_skb_lost
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_update_pacing_rate
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff81cfee9e)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:skb_still_in_host_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_tso_segs
  - net/ipv4/tcp_output.c:tcp_tso_segs
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06383)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d07437)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0f1fa)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0fd95)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d10f05)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d1399e)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81d14245)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/datagram.c (ffffffff81d15440)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81d15afb)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81d19a7d)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_sock
  - net/ipv4/udp.c:udp_read_sock
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81d23c0b)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81d26d58)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff81d2c786)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff81d33df5)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34db5)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81d434aa)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81d4afca)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff81d511e5)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81d56085)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff81d59d47)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff81d5aa74)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff81d5b712)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c95e)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/xfrm/espintcp.c (ffffffff81d7aedc)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81d7ddc8)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_get_first
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffff81d8543d)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81d86aae)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81d87206)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff81d90df5)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81d9bd8d)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81da46b3)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff81dac15e)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db0be6)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/udp.c (ffffffff81dba91b)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81dbe1a8)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff81dbfbc1)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81dc65c4)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb3cc)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81dcdcba)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81dcecf3)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
```
```
In net/ipv6/datagram.c (ffffffff81dd1101)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd4456)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81dd49fd)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffff81dd5585)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ioam6.c (ffffffff81dd67b5)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpns_start
```
```
In net/ipv6/ip6mr.c (ffffffff81dd9869)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff81de18aa)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff81de3587)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def5cb)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81df87af)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e14c3a)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81e1673a)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81e23daf)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81e2802a)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff81e2af73)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options_mp_fail
  - net/mptcp/options.c:mptcp_syn_options
  - net/mptcp/options.c:mptcp_syn_options
```
```
In net/mptcp/token.c (ffffffff81e2b837)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm.c (ffffffff81e2d755)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32b05)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_userspace_pm_active
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
```
```
In net/mptcp/sockopt.c (ffffffff81e32f2f)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35fd3)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
```
In net/mctp/af_mctp.c (ffffffff81e37bd5)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
  - net/mctp/af_mctp.c:mctp_sk_hash
  - net/mctp/af_mctp.c:mctp_sk_expire_keys
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
```
```
In net/mctp/device.c (ffffffff81e38825)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
  - net/mctp/device.c:mctp_dump_addrinfo
```
```
In net/mctp/route.c (ffffffff81e39375)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_dump_rtinfo
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
```
```
In net/mctp/neigh.c (ffffffff81e3b31c)
Location: include/net/sock.h:616
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
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
In kernel/audit.c (ffffffff81228106)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff8122ad4f)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/cgroup.c (ffffffff81326055)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_get_netns_cookie_sockopt
```
```
In security/selinux/hooks.c (ffffffff81676dbc)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:647
Inline: True
```
```
In drivers/net/tun.c (ffffffff81bf0562)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff81d94a4f)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff81d9a6d9)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff81db485d)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff81db7e9b)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff81dd8568)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81de065d)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81dfeba9)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_get_netns_cookie_sk_msg
  - net/core/filter.c:bpf_get_netns_cookie_sock_ops
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff81e02955)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/sock_reuseport.c (ffffffff81e04a89)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
```
```
In net/core/net-sysfs.c (ffffffff81e0a7c5)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff81e14f01)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff81e1c13d)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff81e28d6c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff81e4438c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_selftests_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_selftests_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
```
```
In net/sched/sch_api.c (ffffffff81e54fdc)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81e5dc0c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff81e67763)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff81e6f782)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ethtool/netlink.c (ffffffff81e7d0e8)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81e86445)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
```
```
In net/ipv4/route.c (ffffffff81e942e5)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81e9dec6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1f2b)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea517e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bhash2_addr_any_hashbucket
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea59d6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea74d1)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
```
```
In net/ipv4/tcp.c (ffffffff81eac8e6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_fastopen
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81eba84a)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_dsack_extend
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_mark_skb_lost
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_update_pacing_rate
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3eee)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:skb_still_in_host_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_tso_segs
  - net/ipv4/tcp_output.c:tcp_tso_segs
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb799)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecc517)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4d5a)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed5a35)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6c95)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed996e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81eda2b5)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/tcp_plb.c (ffffffff81edb6e5)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_plb.c:tcp_plb_update_state_upon_rto
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
  - net/ipv4/tcp_plb.c:tcp_plb_update_state
```
```
In net/ipv4/datagram.c (ffffffff81edbc30)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81edbecb)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ee046d)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81eeb18b)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81eee708)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff81ef5126)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff81efc275)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81efd2d5)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81f0c496)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81f146da)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff81f1b045)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81f200e5)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff81f240c7)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff81f24ee4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff81f25bc2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f37d2e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/xfrm/espintcp.c (ffffffff81f48149)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:handle_esp
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81f496e8)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/af_inet6.c (ffffffff81f52edd)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81f5463e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81f54d26)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff81f5f535)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81f6aa3d)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81f73b33)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7bb4e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f81efd)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/udp.c (ffffffff81f8aa31)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81f8dff6)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff81f90310)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81f971e4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c45c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81f9eeb3)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81fa0023)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
```
```
In net/ipv6/datagram.c (ffffffff81fa24db)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa5a86)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81fa6086)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffff81fa6cf5)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ioam6.c (ffffffff81fa80d5)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpns_start
```
```
In net/ipv6/ip6mr.c (ffffffff81fab4b9)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb3d8a)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff81fb5c07)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc369b)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81fccca4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81febb4a)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81fed7ca)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ffad6c)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81ffff8a)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff82003123)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options_mp_fail
  - net/mptcp/options.c:mptcp_syn_options
  - net/mptcp/options.c:mptcp_syn_options
```
```
In net/mptcp/token.c (ffffffff82003a07)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm.c (ffffffff82005cb5)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff8200b565)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_userspace_pm_active
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
```
```
In net/mptcp/sockopt.c (ffffffff8200bfa4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
```
In net/mptcp/pm_userspace.c (ffffffff8200ece2)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
```
In net/mctp/af_mctp.c (ffffffff82010e55)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
  - net/mctp/af_mctp.c:mctp_sk_hash
  - net/mctp/af_mctp.c:mctp_sk_expire_keys
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
```
```
In net/mctp/device.c (ffffffff82011b05)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
  - net/mctp/device.c:mctp_dump_addrinfo
```
```
In net/mctp/route.c (ffffffff82012645)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_dump_rtinfo
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_key_add
```
```
In net/mctp/neigh.c (ffffffff820149dc)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
```
In lib/kobject_uevent.c (ffffffff82023f90)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In kernel/audit.c (ffffffff8123e713)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff8124134f)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/cgroup.c (ffffffff81356245)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_get_netns_cookie_sockopt
```
```
In security/selinux/hooks.c (ffffffff816af0bc)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:649
Inline: True
```
```
In drivers/net/tun.c (ffffffff81c48add)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff81e03095)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff81e08f39)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff81e24efd)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff81e2832e)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff81e49188)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81e51ded)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_add
  - net/core/rtnetlink.c:rtnl_mdb_dump
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81e70165)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_get_netns_cookie_sk_msg
  - net/core/filter.c:bpf_get_netns_cookie_sock_ops
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff81e74ec5)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/sock_reuseport.c (ffffffff81e772cd)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
```
```
In net/core/netdev-genl.c (ffffffff81e7d1f5)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_dev_get_dumpit
```
```
In net/core/net-sysfs.c (ffffffff81e7db55)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff81e88811)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff81e904fd)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff81e9e39f)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/sched/sch_api.c (ffffffff81eb088c)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81eb7b5c)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff81ec3543)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff81ecbc02)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ethtool/netlink.c (ffffffff81ed96c5)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81ee2e25)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
```
```
In net/ipv4/route.c (ffffffff81ef2ab5)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81efc690)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efff84)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f0390e)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bhash2_addr_any_hashbucket
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04168)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05c71)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
  - net/ipv4/inet_connection_sock.c:inet_sk_get_local_port_range
```
```
In net/ipv4/tcp.c (ffffffff81f0b116)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_fastopen
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81f18cda)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_dsack_extend
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_mark_skb_lost
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_update_pacing_rate
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff81f221fe)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:skb_still_in_host_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_tso_segs
  - net/ipv4/tcp_output.c:tcp_tso_segs
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a2fb)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2b1f7)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f33a42)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81f34975)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35c45)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f38a4e)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81f39395)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/tcp_plb.c (ffffffff81f3a7a5)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_plb.c:tcp_plb_update_state_upon_rto
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
  - net/ipv4/tcp_plb.c:tcp_plb_update_state
```
```
In net/ipv4/datagram.c (ffffffff81f3ad00)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81f3af1b)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81f4031d)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:compute_score
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81f4aaab)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81f4e0c8)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff81f54a06)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff81f5bca5)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5cd15)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81f6b82e)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81f743ae)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff81f7acb5)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81f7fbe5)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff81f83c57)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff81f84a74)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff81f85ba8)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9771e)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/xfrm/espintcp.c (ffffffff81fa7c49)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:handle_esp
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81fa9358)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/af_inet6.c (ffffffff81fb28c2)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81fb405f)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4736)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff81fbf265)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81fcaa6d)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81fd3c13)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdbd6c)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe2199)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
```
In net/ipv6/udp.c (ffffffff81fea162)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81fee7e7)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff81ff0b64)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81ff7b95)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffceae)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81fff9e3)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff82000b03)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
```
```
In net/ipv6/datagram.c (ffffffff82002d72)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820062be)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff82006904)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffff82007565)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ioam6.c (ffffffff82008a65)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpns_start
```
```
In net/ipv6/ip6mr.c (ffffffff8200bc59)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff8201452a)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff82016318)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820244db)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff8202df97)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/leftover.c (ffffffff82036a50)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/devlink/netlink.c (ffffffff820429cc)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_instance_iter_dumpit
```
```
In net/devlink/dev.c (ffffffff82044c2d)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_reload
```
```
In net/devlink/health.c (ffffffff820482c1)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82067dea)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff8206992c)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff82072c05)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff8207c12a)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:mptcp_space
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff8207f2b3)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options_mp_fail
  - net/mptcp/options.c:mptcp_established_options_add_addr
  - net/mptcp/options.c:mptcp_established_options_dss
  - net/mptcp/options.c:mptcp_syn_options
  - net/mptcp/options.c:mptcp_syn_options
```
```
In net/mptcp/token.c (ffffffff82080380)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
```
```
In net/mptcp/pm.c (ffffffff82082035)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_remove_addr
  - net/mptcp/pm.c:mptcp_pm_announce_addr
```
```
In net/mptcp/pm_netlink.c (ffffffff820879f5)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_userspace_pm_active
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_flags_and_ifindex_by_id
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
```
```
In net/mptcp/sockopt.c (ffffffff82088494)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
```
In net/mptcp/pm_userspace.c (ffffffff8208b8c9)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
```
In net/mctp/af_mctp.c (ffffffff8208dc15)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
  - net/mctp/af_mctp.c:mctp_sk_hash
  - net/mctp/af_mctp.c:mctp_sk_expire_keys
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
```
```
In net/mctp/device.c (ffffffff8208e8e5)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
  - net/mctp/device.c:mctp_dump_addrinfo
```
```
In net/mctp/route.c (ffffffff8208f435)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_dump_rtinfo
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_key_add
```
```
In net/mctp/neigh.c (ffffffff820917fc)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
```
In net/handshake/netlink.c (ffffffff82092605)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
```
In net/handshake/request.c (ffffffff820937c5)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_sk_destruct
```
```
In lib/kobject_uevent.c (ffffffff820a4090)
Location: include/net/sock.h:649
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In kernel/audit.c (ffffffff81258645)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff8125b17e)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/cgroup.c (ffffffff8137ed75)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_get_netns_cookie_sockopt
```
```
In security/selinux/hooks.c (ffffffff816ec10b)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:632
Inline: True
```
```
In security/apparmor/af_inet.c (ffffffff81762eb8)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:aa_inet_bind_perm
```
```
In drivers/net/tun.c (ffffffff81cfe43d)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff81ebfa95)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff81ec59a9)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff81ee2e5d)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff81ee6318)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff81f07e78)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff81f10ecd)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_mdb_del
  - net/core/rtnetlink.c:rtnl_mdb_add
  - net/core/rtnetlink.c:rtnl_mdb_get
  - net/core/rtnetlink.c:rtnl_mdb_dump
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81f2a3e5)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_get_netns_cookie_sk_msg
  - net/core/filter.c:bpf_get_netns_cookie_sock_ops
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff81f34765)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/sock_reuseport.c (ffffffff81f3728d)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
```
```
In net/core/netdev-genl.c (ffffffff81f3e18c)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_queue_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_napi_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_dev_get_dumpit
```
```
In net/core/net-sysfs.c (ffffffff81f3eac5)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/page_pool_user.c (ffffffff81f44f77)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_dump
```
```
In net/core/fib_rules.c (ffffffff81f4a821)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff81f528cd)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff81f60b1b)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6a0b5)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
```
```
In net/sched/sch_api.c (ffffffff81f732fc)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f7ab6c)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (0)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff81f86963)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff81f8f122)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_start
```
```
In net/ethtool/netlink.c (ffffffff81f9d80e)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81fa6cc0)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
```
```
In net/ipv4/route.c (ffffffff81fb6a45)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81fc05d0)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc4344)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7b8a)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bhash2_addr_any_hashbucket
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc84a0)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9dd1)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
```
```
In net/ipv4/tcp.c (ffffffff81fcede6)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:__tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_sendmsg_fastopen
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81fdd49c)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_rcv_spurious_retrans
  - net/ipv4/tcp_input.c:tcp_dsack_extend
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_check_dsack
  - net/ipv4/tcp_input.c:tcp_mark_skb_lost
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_update_pacing_rate
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5ebe)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_tso_segs
  - net/ipv4/tcp_output.c:tcp_tso_segs
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff81feee49)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81fefea7)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9bb6)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffaaf5)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffbcf5)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffeb2e)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81fff485)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/tcp_plb.c (ffffffff82000765)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/tcp_plb.c:tcp_plb_update_state_upon_rto
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
  - net/ipv4/tcp_plb.c:tcp_plb_update_state
```
```
In net/ipv4/datagram.c (ffffffff82000dee)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8200102b)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff82005ca0)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:compute_score
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff82010bbb)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff820141f8)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff8201ac56)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:__inet_listen_sk
```
```
In net/ipv4/igmp.c (ffffffff82022205)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff820232a5)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff82031b2e)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff8203ab4e)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff820413b5)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff82046265)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff8204a307)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff8204b232)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
```
In net/ipv4/tcp_cubic.c (ffffffff8204c278)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
  - net/ipv4/tcp_cubic.c:hystart_update
```
```
In net/ipv4/tcp_ao.c (ffffffff820568fc)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
  - net/ipv4/tcp_ao.c:tcp_ao_connect_init
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_ao_syncookie
  - net/ipv4/tcp_ao.c:tcp_v4_ao_lookup
  - net/ipv4/tcp_ao.c:tcp_v4_ao_lookup_rsk
  - net/ipv4/tcp_ao.c:tcp_ao_ignore_icmp
```
```
In net/xfrm/xfrm_policy.c (ffffffff82064a90)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/xfrm/espintcp.c (ffffffff82074f09)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:handle_esp
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff820767e8)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/af_inet6.c (ffffffff82080052)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff8208190f)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff82081fe6)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff8208c705)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8209820d)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff820a1523)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff820a989c)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820b0141)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_set_mcast_msfilter
```
```
In net/ipv6/udp.c (ffffffff820b80fb)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff820bc3ba)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff820be758)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff820c57e5)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c7f3e)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff820ce7df)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff820cf943)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
```
```
In net/ipv6/datagram.c (ffffffff820d1d49)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d511e)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff820d5764)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffff820d6375)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ioam6.c (ffffffff820d7985)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpns_start
```
```
In net/ipv6/ip6mr.c (ffffffff820dac29)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff820e366a)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff820e5372)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f37eb)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/ipv6/tcp_ao.c (ffffffff820f4aca)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ipv6/tcp_ao.c:tcp_v6_ao_lookup_rsk
  - net/ipv6/tcp_ao.c:tcp_v6_ao_lookup
```
```
In net/packet/af_packet.c (ffffffff820fda17)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/netlink.c (ffffffff82101caa)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_dumpit
  - net/devlink/netlink.c:devlink_nl_dumpit
```
```
In net/devlink/dev.c (ffffffff821044ed)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_reload_doit
```
```
In net/devlink/region.c (ffffffff8211101c)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_read_dumpit
```
```
In net/devlink/health.c (ffffffff821143e3)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b06a)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff8213cccc)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff8214ab29)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_unaccepted_force_close
  - net/mptcp/protocol.c:mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_active
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:__mptcp_error_report
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff821515fa)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:__mptcp_sync_state
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v6_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/subflow.c:subflow_v4_route_req
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_check_req
```
```
In net/mptcp/options.c (ffffffff821547a3)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options_mp_fail
  - net/mptcp/options.c:mptcp_established_options_add_addr
  - net/mptcp/options.c:mptcp_syn_options
  - net/mptcp/options.c:mptcp_syn_options
```
```
In net/mptcp/token.c (ffffffff82155870)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
```
```
In net/mptcp/ctrl.c (ffffffff821561ee)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/mptcp/ctrl.c:mptcp_close_timeout
```
```
In net/mptcp/pm.c (ffffffff82157625)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_remove_addr
  - net/mptcp/pm.c:mptcp_pm_announce_addr
```
```
In net/mptcp/pm_netlink.c (ffffffff8215d255)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_userspace_pm_active
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_dumpit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_flags_and_ifindex_by_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
```
```
In net/mptcp/sockopt.c (ffffffff821602f8)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_set_rcvlowat
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
```
In net/mptcp/pm_userspace.c (ffffffff821616ca)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit
```
```
In net/mctp/af_mctp.c (ffffffff821640d5)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
  - net/mctp/af_mctp.c:mctp_sk_hash
  - net/mctp/af_mctp.c:mctp_sk_expire_keys
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
```
```
In net/mctp/device.c (ffffffff82164dd5)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
  - net/mctp/device.c:mctp_dump_addrinfo
```
```
In net/mctp/route.c (ffffffff82165915)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_dump_rtinfo
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_key_add
```
```
In net/mctp/neigh.c (ffffffff82167d9c)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
```
In net/handshake/netlink.c (ffffffff82168ee5)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
```
In net/handshake/request.c (ffffffff8216a075)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_sk_destruct
```
```
In net/handshake/trace.c (ffffffff8216cae3)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - net/handshake/trace.c:perf_trace_tls_contenttype
  - net/handshake/trace.c:perf_trace_handshake_alert_class
  - net/handshake/trace.c:trace_event_raw_event_tls_contenttype
  - net/handshake/trace.c:trace_event_raw_event_handshake_alert_class
```
```
In lib/kobject_uevent.c (ffffffff8217c160)
Location: include/net/sock.h:632
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In kernel/audit.c (ffff8000101ebec0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffff8000101ede94)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (ffff80001054f840)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2473
Inline: True
```
```
In drivers/net/tun.c (ffff8000109df584)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffff800010ba6bd0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffff800010ba9ac0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffff800010bc1914)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffff800010bc3e54)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffff800010be5570)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffff800010bec4f4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffff800010bf8508)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffff800010c0384c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/net-sysfs.c (ffff800010c08c20)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffff800010c13e30)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffff800010c17794)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffff800010c1e9bc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffff800010c2bc68)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
```
```
In net/sched/sch_api.c (ffff800010c3c8e4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffff800010c443d8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffff800010c47710)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffff800010c4b7d0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_undo_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_compare
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffff800010c5183c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffff800010c5c9c0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffff800010c65978)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffff800010c66840)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6b204)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6b944)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6ca28)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffff800010c75818)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffff800010c7a4ec)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffff800010c88254)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffff800010c88b14)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ba70)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c906a4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffff800010c90f70)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffff800010c923b0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c9419c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffff800010c94b14)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (ffff800010c95c9c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffff800010c9683c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffff800010c9ad58)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
```
```
In net/ipv4/icmp.c (ffff800010ca41f4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffff800010ca58c8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffff800010cac07c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffff800010cb2cd8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffff800010cb39d8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffff800010cc0578)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffff800010cc4788)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffff800010cc8930)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffff800010cc9e28)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffff800010cd1108)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffff800010cd20c4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffff800010cd2f60)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce1674)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/unix/af_unix.c (ffff800010ceefec)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffff800010cf62b0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffff800010cf797c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffff800010cf8c78)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffff800010d02898)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffff800010d0b7d4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffff800010d112dc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffff800010d1a6a0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1cbd8)
Location: include/net/sock.h:2473
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d25ae4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffff800010d2a1d0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffff800010d2b898)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffff800010d31ebc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38aa8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_stream_memory_free
```
```
In net/ipv6/ping.c (ffff800010d3a5a4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffff800010d3c310)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/datagram.c (ffff800010d3cc2c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3fe54)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/inet6_connection_sock.c (ffff800010d4097c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffff800010d41448)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffff800010d42198)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffff800010d4ad18)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffff800010d4c640)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55ea8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffff800010d5c0ec)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dcb/dcbnl.c (ffff800010d6f2b4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d3cc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffff800010d7ea48)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In lib/kobject_uevent.c (ffff800010d8c80c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (c042bb28)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (c042dfc4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (c07091d8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2473
Inline: True
```
```
In drivers/net/tun.c (c0ac7158)
Location: include/net/sock.h:2473
Inline: True
```
```
In net/socket.c (c0cc6294)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (c0cc808c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (c0cdc80c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (c0cdf300)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (c0d0016c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (c0d04bfc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_calcit
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (c0d12164)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (c0d1cbe8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/net-sysfs.c (c0d21c6c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (c0d2b85c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_nl2rule
```
```
In net/core/net-traces.c (c0d2de3c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (c0d36a00)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (c0d42808)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
```
```
In net/sched/sch_api.c (c0d4e0dc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (c0d54f40)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (c0d58500)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (c0d5bd34)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_undo_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (c0d60f70)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (c0d6c08c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (c0d755b4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (c0d76a08)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (c0d7a2c4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a9c0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (c0d7b704)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (c0d7ed34)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (c0d87f00)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (c0d97528)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_small_queue_check
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (c0d978e0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (c0d9a130)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
```
```
In net/ipv4/tcp_minisocks.c (c0d9ee54)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (c0d9fc20)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (c0da0f00)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (c0da29f8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_no_cookie
```
```
In net/ipv4/tcp_recovery.c (c0da33b4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (c0da43fc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da4ed0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (c0da7e84)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (c0db035c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (c0db2230)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (c0db8a14)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (c0dbe788)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (c0dbf278)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (c0dcb3b8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
  - net/ipv4/ping.c:ping_get_first
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (c0dd01b4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (c0dd3cf0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (c0dd5d94)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (c0ddaaec)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (c0ddbf50)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (c0ddcad8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/xfrm/xfrm_policy.c (c0deaa4c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/unix/af_unix.c (c0df69d0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (c0dfcddc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (c0dfdfcc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (c0dfeb50)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (c0e086d4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (c0e116c4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (c0e15658)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (c0e1e7a8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_table
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (c0e2189c)
Location: include/net/sock.h:2473
Inline: True
```
```
In net/ipv6/udp.c (c0e2935c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (c0e2e180)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (c0e2f480)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (c0e34d64)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (c0e3ae68)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_stream_memory_free
```
```
In net/ipv6/ping.c (c0e3ca98)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (c0e3f51c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/datagram.c (c0e3fe88)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (c0e42cd8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/inet6_connection_sock.c (c0e43358)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (c0e43e28)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (c0e44ae4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (c0e4c044)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (c0e4d8ec)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (c0e56428)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (c0e5c11c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dcb/dcbnl.c (c0e6cf24)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (c0e77278)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (c0e78d7c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In lib/kobject_uevent.c (c0e86bec)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (c00000000025d790)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (c000000000260960)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (c0000000006b0d68)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2473
Inline: True
```
```
In drivers/net/tun.c (c000000000aa451c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (c000000000c7abf8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (c000000000c7efd4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (c000000000c9a77c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (c000000000c9e18c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (c000000000cc9710)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (c000000000ccf634)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (c000000000cdf300)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (c000000000ced0d4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/net-sysfs.c (c000000000cf35b8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (c000000000d01418)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (c000000000d04aa0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (c000000000d10b18)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (c000000000d2256c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
```
```
In net/sched/sch_api.c (c000000000d36698)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (c000000000d3f894)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (c000000000d445a0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (c000000000d4b8f0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_undo_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_compare
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (c000000000d501e0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (c000000000d5eec4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (c000000000d6a0c4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (c000000000d6b080)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (c000000000d70704)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70ff8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72358)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (c000000000d76ddc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (c000000000d8504c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (c000000000d95164)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (c000000000d95660)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (c000000000d983a8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9f220)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (c000000000da0544)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (c000000000da2a14)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (c000000000da4934)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (c000000000da5398)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (c000000000da749c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c000000000da8298)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (c000000000dabaac)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (c000000000db6e20)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (c000000000db9880)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (c000000000dbff24)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (c000000000dc9e20)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (c000000000dcb250)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (c000000000dda898)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
  - net/ipv4/ping.c:ping_get_first
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (c000000000de07bc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (c000000000de5cdc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (c000000000de922c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (c000000000dee91c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (c000000000df04bc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (c000000000df1278)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/xfrm/xfrm_policy.c (c000000000e03db0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/unix/af_unix.c (c000000000e14b74)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (c000000000e1c884)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (c000000000e1e3b4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (c000000000e1f13c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (c000000000e2a210)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (c000000000e35f6c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (c000000000e3a68c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (c000000000e488a0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4af2c)
Location: include/net/sock.h:2473
Inline: True
```
```
In net/ipv6/udp.c (c000000000e556b8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (c000000000e5b0a4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (c000000000e5cdb8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (c000000000e64160)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b440)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_stream_memory_free
```
```
In net/ipv6/ping.c (c000000000e6d7b8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (c000000000e6ff6c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/datagram.c (c000000000e70794)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e74760)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/inet6_connection_sock.c (c000000000e74fe0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (c000000000e75dc0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (c000000000e76f6c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (c000000000e80ec4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (c000000000e82d18)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8ef28)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (c000000000e97adc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dcb/dcbnl.c (c000000000eae108)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebbaa4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (c000000000ebe260)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In lib/kobject_uevent.c (c000000000ecd9e8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffe000160640)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffe0001622ec)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (ffffffe0003a9632)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2473
Inline: True
```
```
In drivers/net/tun.c (ffffffe0006295d8)
Location: include/net/sock.h:2473
Inline: True
```
```
In net/socket.c (ffffffe00073b1e0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffe00073cfec)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffe00074e380)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffe00075088c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffe00076c0b0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffe00076fe84)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffe00077a1ee)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffe0007828c2)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/net-sysfs.c (ffffffe0007869a6)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffe00078f49e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffe0007916ec)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffe0007985da)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffe0007a333c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
```
```
In net/sched/sch_api.c (ffffffe0007ad2b8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007b2794)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffe0007b5452)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffe0007b9c1a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_undo_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_compare
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffe0007bc9fe)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffe0007c5830)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffe0007cd0b2)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cdfea)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d0ea6)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d1396)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d233e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffe0007d4afe)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffe0007de154)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffe0007e9492)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9812)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb59c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007f01de)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffe0007f0d88)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f21a8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f375e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffe0007f3e7e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (ffffffe0007f5122)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffe0007f5a62)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffe0007f7536)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffe0007ff504)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffe00080119a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffe000804f2c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffe00080b0e8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b802)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffe000815688)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
  - net/ipv4/ping.c:ping_get_first
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffe000819c14)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffe00081cbb8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffe00081f334)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffe000822400)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffe0008234ae)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffe000823d0c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/xfrm/xfrm_policy.c (ffffffe000830180)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/unix/af_unix.c (ffffffe00083c0b8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffe000841b74)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffe000842c9e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffe000843634)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffe00084ac82)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffe000852892)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffe000855fa8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffe00085de66)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe0008604aa)
Location: include/net/sock.h:2473
Inline: True
```
```
In net/ipv6/udp.c (ffffffe00086652c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffe00086aa10)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffe00086ba4a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffe000870762)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875cf2)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_stream_memory_free
```
```
In net/ipv6/ping.c (ffffffe000877246)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffe000878d72)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/datagram.c (ffffffe0008791aa)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087bc68)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/inet6_connection_sock.c (ffffffe00087c24c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffe00087cb8a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffe00087d7da)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffe000883e18)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffe0008853be)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d74c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffe000892302)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dcb/dcbnl.c (ffffffe0008a0e80)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aa2be)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffe0008abde6)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In lib/kobject_uevent.c (ffffffe0008b501a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff8116f55f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff81171373)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (ffffffff8145a756)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2473
Inline: True
```
```
In drivers/net/tun.c (ffffffff81788eb1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff818ae66a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff818b1fdb)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff818c568e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff818c7a54)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff818e52c1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818ea259)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff818f6d0c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff818ffff5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/net-sysfs.c (ffffffff819042e5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff8190d731)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff8190f90c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff81917fab)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff8192347b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
```
```
In net/sched/sch_api.c (ffffffff81930109)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff819370cf)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff8193a350)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff8193e958)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_undo_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff81942461)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff8194c6a3)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8195501a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81955895)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff819598b7)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959e1e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195abff)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff81962a90)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff8196867a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff81975405)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff8197578c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81978278)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197ceb9)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff8197d905)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197ee65)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819803d0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81980b25)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (ffffffff81981e95)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81982799)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81985df9)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff8198d906)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff8198f811)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff81993ec3)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff8199aef5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff8199bc75)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff819a7304)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff819aaf3d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff819ae895)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff819b109c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff819b47b5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff819b5a47)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff819b6474)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c3ab5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/unix/af_unix.c (ffffffff819cf198)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffff819d4f63)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff819d6375)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff819d6c6d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff819dea55)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819e7af8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819eb3ec)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff819f433c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f6f9c)
Location: include/net/sock.h:2473
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819ff6db)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81a03764)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a04cd6)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81a09f90)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f816)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_stream_memory_free
```
```
In net/ipv6/ping.c (ffffffff81a111fc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a12f7d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/datagram.c (ffffffff81a13860)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a1632f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a169a8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffff81a17485)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff81a180da)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1eee1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff81a20456)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a28724)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81a2e55f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dcb/dcbnl.c (ffffffff81a3dc41)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a48199)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81a4a85d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In lib/kobject_uevent.c (ffffffff81a50b52)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff811626ff)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff81164513)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (ffffffff8144b186)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2473
Inline: True
```
```
In drivers/net/tun.c (ffffffff81768801)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/vxlan.c (ffffffff817708d0)
Location: include/net/sock.h:2473
Inline: True
```
```
In net/socket.c (ffffffff818685ba)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff8186bf2b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff8187f5ce)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff81881994)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff8189f101)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff818a4099)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff818b0b3c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff818b9e25)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/net-sysfs.c (ffffffff818be115)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff818c74f1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff818c96cc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff818d1d5b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff818dd22b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
```
```
In net/sched/sch_api.c (ffffffff818e9c09)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff818f0bcf)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff818f3e50)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff818f8458)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_undo_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff818fbf51)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff81906193)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8190eb0a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff8190f385)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff819133a7)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8191390e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819146ef)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff8191c580)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff8192216a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff8192eec5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f24c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81931d38)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936979)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819373c5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938925)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939e90)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff8193a5e5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (ffffffff8193b955)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8193c259)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff8193f8b9)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff819473c6)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff819492d1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff8194d983)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff819549b5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81955735)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81960dc4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff819649fd)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff8196aec5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff8196d6cc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff81970de5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/udp_tunnel.c (ffffffff81971bf5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/udp_tunnel.c:udp_tunnel_notify_del_rx_port
  - net/ipv4/udp_tunnel.c:udp_tunnel_notify_add_rx_port
```
```
In net/ipv4/syncookies.c (ffffffff81972837)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff81973264)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/xfrm/xfrm_policy.c (ffffffff819808a5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/unix/af_unix.c (ffffffff8198bf58)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffff81991d23)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81993135)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81993a2d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff8199b815)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a48b8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff819a81ac)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff819b10fc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b3d5c)
Location: include/net/sock.h:2473
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bc49b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff819c0524)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff819c1a96)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff819c6d50)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc5d6)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_stream_memory_free
```
```
In net/ipv6/ping.c (ffffffff819cdfbc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff819cfd3d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/datagram.c (ffffffff819d0620)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d30ef)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d3768)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffff819d4245)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff819d4e9a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff819dbca1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff819dd216)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e54e4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff819eb74f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dcb/dcbnl.c (ffffffff819fa831)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a04d89)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81a0744d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In lib/kobject_uevent.c (ffffffff81a0dc52)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff8116d32f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff8116f143)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (ffffffff814567f6)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2473
Inline: True
```
```
In drivers/net/tun.c (ffffffff817b9251)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff818ff66a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff81902fdb)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff8191668e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff81918a54)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff819362f1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8193b289)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81947d3c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff81951025)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/net-sysfs.c (ffffffff81955315)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff8195e761)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff8196093c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff8196913b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff8197460b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
```
```
In net/sched/sch_api.c (ffffffff81981299)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff8198825f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff8198b4e0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff8198fae8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_undo_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff819935f1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/netfilter/nfnetlink.c (ffffffff8199886b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_msg
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a44ff)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst
  - net/netfilter/nf_conntrack_proto.c:getorigdst
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ae652)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_stat_cpu_dump
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_stat_ct
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_ct_stat_cpu_dump
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_list
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
```
```
In net/ipv4/route.c (ffffffff819b6e73)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819bf7ea)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c0065)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c4087)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c45ee)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c53cf)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff819cd260)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819d2e4a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff819dfbd5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff819dff5c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e2a48)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e7689)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819e80d5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9635)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819eaba0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819eb2f5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (ffffffff819ec665)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819ecf69)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff819f05c9)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff819f81a6)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff819fa0b1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff819fe763)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff81a05795)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06515)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81a11ba4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81a157dd)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff81a19135)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81a1b93c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f055)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff81a202e7)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a20ef4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2e535)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/unix/af_unix.c (ffffffff81a39c18)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffff81a3f9e3)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81a40df5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a416ed)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff81a494d5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a52578)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a55e6c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5edbc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a61a1c)
Location: include/net/sock.h:2473
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6a15b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81a6e1e4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a6f756)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81a74a10)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a296)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_stream_memory_free
```
```
In net/ipv6/ping.c (ffffffff81a7bc7c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d9fd)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/datagram.c (ffffffff81a7e2e0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a80daf)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a81428)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffff81a81f05)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff81a82b5a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff81a89961)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff81a8aed6)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a942d4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81a9a10f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dcb/dcbnl.c (ffffffff81aa9af1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4049)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81ab670d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In lib/kobject_uevent.c (ffffffff81abcf42)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff8117ab25)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditfilter.c (ffffffff8117c933)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In security/selinux/hooks.c (ffffffff81471ae6)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:2473
Inline: True
```
```
In drivers/net/tun.c (ffffffff817d4c4e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff8192065a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:__sys_listen
  - net/socket.c:sock_ioctl
```
```
In net/core/sock.c (ffffffff81923f4b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_net_capable
```
```
In net/core/net_namespace.c (ffffffff8193788e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/flow_dissector.c (ffffffff81939cbc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/neighbour.c (ffffffff81957a81)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/core/rtnetlink.c (ffffffff8195cadd)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_fdb_del
  - net/core/rtnetlink.c:rtnl_fdb_add
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff8196964c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
  - net/core/filter.c:bpf_tcp_check_syncookie
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_diag.c (ffffffff81972965)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
```
```
In net/core/net-sysfs.c (ffffffff81977395)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_netlink_ns
```
```
In net/core/fib_rules.c (ffffffff819809c1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/core/net-traces.c (ffffffff81982bac)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
```
```
In net/core/lwt_bpf.c (ffffffff8198b51b)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff81996afb)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
```
```
In net/sched/sch_api.c (ffffffff819a3819)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
```
In net/sched/cls_api.c (ffffffff819aa4cf)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
```
In net/sched/act_api.c (ffffffff819add50)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tc_ctl_action
```
```
In net/netlink/af_netlink.c (ffffffff819b2488)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_undo_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netlink/genetlink.c (ffffffff819b60e1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (ffffffff819c06f3)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819c916a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c99f5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cdaf5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce18e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819ceea4)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff819d6dee)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:skb_entail
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819dc9eb)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_output.c (ffffffff819e9885)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_select_initial_window
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9c1a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ec8b8)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_stream_memory_free
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f1359)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819f1df5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f33b5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f4a20)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819f5175)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_update_reo_wnd
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (ffffffff819f654f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819f6e59)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:__raw_v4_lookup
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff819fb649)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81a024a6)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81a043c0)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
```
In net/ipv4/af_inet.c (ffffffff81a08af3)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/igmp.c (ffffffff81a0fd65)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10b95)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:inet_dump_fib
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
```
In net/ipv4/ping.c (ffffffff81a1c510)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81a2021d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffff81a23bd5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81a2681c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2a575)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
```
```
In net/ipv4/syncookies.c (ffffffff81a2b7e7)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a2c23e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a39d25)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
```
```
In net/unix/af_unix.c (ffffffff81a46258)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_find_socket_byname
```
```
In net/ipv6/af_inet6.c (ffffffff81a4b50d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81a4c9f5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d34d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/addrconf.c (ffffffff81a553f5)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e578)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_dump
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff81a61e9c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_delroute
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6b23c)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6dedc)
Location: include/net/sock.h:2473
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a7678a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81a7a945)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a7bd86)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81a810d2)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86ad6)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_stream_memory_free
```
```
In net/ipv6/ping.c (ffffffff81a884cc)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a8a24d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
```
In net/ipv6/datagram.c (ffffffff81a8ab61)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8d66f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a8dd02)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/seg6.c (ffffffff81a8e815)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f42a)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
```
In net/ipv6/fib6_rules.c (ffffffff81a965c1)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
```
In net/ipv6/syncookies.c (ffffffff81a97b37)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa041f)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff81aa6e3e)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dcb/dcbnl.c (ffffffff81ab5e61)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_doit
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac03e9)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81ac276d)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In lib/kobject_uevent.c (ffffffff81ac93c2)
Location: include/net/sock.h:2473
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
</ul>

## Differences
