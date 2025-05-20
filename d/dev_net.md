# Function: <code>dev_net</code>

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
In security/selinux/hooks.c (0)
Location: include/linux/netdevice.h:1938
Inline: True
```
```
In security/selinux/netif.c (ffffffff8134ce06)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff815e967a)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff815f00cf)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f6b94)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/dev.c (ffffffff817146ac)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_run_todo
```
```
In net/core/dst.c (0)
Location: include/linux/netdevice.h:1938
Inline: True
```
```
In net/core/neighbour.c (ffffffff81724599)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_notify
```
```
In net/core/rtnetlink.c (ffffffff8172a582)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
```
```
In net/core/filter.c (ffffffff81731a1e)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:skb_do_redirect
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/netdevice.h:1938
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/netdevice.h:1938
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81739934)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/sched/sch_api.c (ffffffff8174425f)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/ematch.c (ffffffff81749bd5)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/netfilter/core.c (0)
Location: include/linux/netdevice.h:1938
Inline: True
```
```
In net/ipv4/route.c (ffffffff81752f62)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:rt_set_nexthop
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/ipv4/ip_input.c (ffffffff81758948)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_forward.c (ffffffff8175a799)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff8175bd5d)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/netdevice.h:1938
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d7bf)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781afb)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff8178584f)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff817894d2)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/arp.c (ffffffff818170de)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:parp_redo
```
```
In net/ipv4/icmp.c (ffffffff8178dc5f)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_err
```
```
In net/ipv4/devinet.c (ffffffff8178f51d)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (ffffffff8179537c)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff8179a751)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
```
In net/ipv4/ping.c (ffffffff817a2f11)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_rcv
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a47ad)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff817a80c4)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/xfrm4_input.c (ffffffff817aff14)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b120e)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dev_event
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff817bb9ce)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc5d7)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/netdevice.h:1938
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c68b2)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff817c8653)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff817c9811)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
```
In net/ipv6/route.c (ffffffff817d3282)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_ins_rt
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:rt6_remove_prefsrc
```
```
In net/ipv6/ndisc.c (ffffffff817de9c3)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff817e3e19)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff817e6a2a)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff817e738c)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff817e9135)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff817edd05)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817ef27f)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f2dbc)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff817f8168)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6_mr_input
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/netdevice.h:1938
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff817fcb6b)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffff817fee65)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/netdevice.h:1938
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff818018e9)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/packet/af_packet.c (ffffffff81803d85)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/netdevice.h:1938
Inline: True
```
```
In net/wireless/wext-proc.c (0)
Location: include/linux/netdevice.h:1938
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:1938
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81814c47)
Location: include/linux/netdevice.h:1938
Inline: True
Inline callers:
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
In security/selinux/hooks.c (0)
Location: include/linux/netdevice.h:2015
Inline: True
```
```
In security/selinux/netif.c (ffffffff81382db6)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff81647dca)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff8164f4ff)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81656d3d)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/dev.c (ffffffff8177e977)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/dst.c (0)
Location: include/linux/netdevice.h:2015
Inline: True
```
```
In net/core/neighbour.c (ffffffff817908ea)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff81793faf)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff8179e720)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/netdevice.h:2015
Inline: True
```
```
In net/core/net-procfs.c (0)
Location: include/linux/netdevice.h:2015
Inline: True
```
```
In net/core/fib_rules.c (ffffffff817a5c44)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/sched/sch_api.c (ffffffff817b127f)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/ematch.c (ffffffff817b6b45)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/netfilter/core.c (0)
Location: include/linux/netdevice.h:2015
Inline: True
```
```
In net/ipv4/route.c (ffffffff817c3ed5)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff817c5228)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff817c6b57)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff817c7fdd)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff817cb669)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ebbf7)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff817eefbb)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff817f2e4d)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff817f7f1c)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff817fa776)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff817fcace)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff817fdfe8)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff818049cb)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff8180947c)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b9f1)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffff81811da5)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81812418)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81815afc)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181ce0c)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181e15e)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dev_event
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81828911)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818294f7)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/netdevice.h:2015
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff818339b2)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff818361ff)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81838e3b)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/route.c (ffffffff81840c82)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_ins_rt
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ndisc.c (ffffffff8184d7b3)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff8185287f)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81854fa6)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81857083)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff818594c1)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8185c682)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860738)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81861bd0)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81866c51)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8186afd9)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/netdevice.h:2015
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff8186c4bb)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffff8186e805)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/netdevice.h:2015
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81874d45)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/netdevice.h:2015
Inline: True
```
```
In net/wireless/wext-proc.c (0)
Location: include/linux/netdevice.h:2015
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2015
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81887b17)
Location: include/linux/netdevice.h:2015
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
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
In security/selinux/hooks.c (0)
Location: include/linux/netdevice.h:1997
Inline: True
```
```
In security/selinux/netif.c (ffffffff81399836)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff81678eca)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff81681829)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81684a1d)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/dev.c (ffffffff817ac267)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/dst.c (0)
Location: include/linux/netdevice.h:1997
Inline: True
```
```
In net/core/neighbour.c (ffffffff817be19a)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff817c182f)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff817cd17e)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffffffff817d220e)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (0)
Location: include/linux/netdevice.h:1997
Inline: True
```
```
In net/core/fib_rules.c (ffffffff817d4714)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/sched/sch_api.c (ffffffff817e09ff)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (0)
Location: include/linux/netdevice.h:1997
Inline: True
```
```
In net/sched/ematch.c (ffffffff817e65d3)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/netfilter/core.c (0)
Location: include/linux/netdevice.h:1997
Inline: True
```
```
In net/ipv4/route.c (ffffffff817f39f5)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff817f4d38)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff817f6657)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff817f7acd)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff817fb2c9)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c56c)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff8182004b)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81823c2d)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81828dbc)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff8182b646)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff8182da2e)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff8182ef48)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff8183599b)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff8183a58c)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff8183cb11)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffff818432b5)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843928)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818472ac)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e6dc)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184f9de)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dev_event
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a2f1)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8185aec7)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/netdevice.h:1997
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8186542c)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81867d0f)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff8186a85b)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
```
In net/ipv6/route.c (ffffffff81872952)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_ins_rt
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ndisc.c (ffffffff8187f663)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff8188457f)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81886d16)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81888e83)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff8188b2f1)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8188e592)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818926ef)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81894175)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81899351)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8189de29)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/netdevice.h:1997
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff8189f2cb)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffff818a1755)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a414a)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/netdevice.h:1997
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/netdevice.h:1997
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818a9205)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/netdevice.h:1997
Inline: True
```
```
In net/wireless/wext-proc.c (0)
Location: include/linux/netdevice.h:1997
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:1997
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff818bc337)
Location: include/linux/netdevice.h:1997
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
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
In security/selinux/hooks.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In security/selinux/netif.c (ffffffff813afc46)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff8168d7a6)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff81696669)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81699cd0)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/dev.c (ffffffff817d39cf)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/dst.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/core/neighbour.c (ffffffff817dcc19)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff817dffef)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff817ec5be)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffffffff817f15ee)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/core/fib_rules.c (ffffffff817f3a04)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/sched/sch_api.c (ffffffff817ffebc)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/sched/ematch.c (ffffffff81806101)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/netfilter/core.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/ipv4/route.c (ffffffff81813de5)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff818151c8)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff81816a69)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81817e53)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff8181b686)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cde5)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff818407e3)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff8184490d)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8184a09b)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff8184ca36)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff8184eeb0)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff818503f7)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
```
In net/ipv4/igmp.c (ffffffff81856edb)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff8185baf7)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e230)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffff81864b05)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81865188)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81868c9c)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/xfrm4_input.c (ffffffff81872136)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8187867b)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e15d)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ee44)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81889c0e)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8188c51f)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff8188ed9b)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8189a81c)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_ins_rt
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ndisc.c (ffffffff818a5747)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff818aa1ab)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff818ad205)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff818af569)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff818b105c)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff818b4bd5)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8d1d)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff818bb635)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff818bf558)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff818c4449)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff818c582b)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffff818c7da5)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca74b)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818cfc55)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/wireless/wext-proc.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2021
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff818e2d27)
Location: include/linux/netdevice.h:2021
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
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
In security/selinux/hooks.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In security/selinux/netif.c (ffffffff813d5cf6)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff816f7326)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff81701470)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8170447c)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
```
```
In net/core/dev.c (ffffffff8184debd)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/dst.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/core/neighbour.c (ffffffff818577e9)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff8185a8bf)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
```
```
In net/core/filter.c (ffffffff818683ee)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffffffff8186cbce)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/core/fib_rules.c (ffffffff8186f0f4)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/sched/sch_api.c (ffffffff8187dc5c)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff818801f3)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81882ae5)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/netfilter/core.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/ipv4/route.c (ffffffff81893445)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff81894398)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff81895c29)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8189a5bc)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc511)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bff53)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff818c4339)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff818c9c32)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff818cc6f6)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff818cec30)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff818d0027)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff818d6d8b)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff818db9e7)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff818de270)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffff818e4c65)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e52e8)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818e91dc)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2b16)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8f8b)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff818feba3)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818fff64)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8190adfe)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8190d80f)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff819103eb)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8191d5ac)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:ip6_ins_rt
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81922e5e)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In net/ipv6/ndisc.c (ffffffff81928147)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff8192cc03)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff8192fe15)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff8193227f)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff819336ac)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81937945)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193bbe4)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff8193e6be)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81942611)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819476df)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948b3b)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffff8194b345)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e359)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8194fc63)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81954b25)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/wireless/wext-proc.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2037
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffff81968b17)
Location: include/linux/netdevice.h:2037
Inline: True
Inline callers:
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
In kernel/bpf/offload.c (ffffffff811cb8da)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffffffff813fe453)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffffffff81406306)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff817344b5)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff8173de99)
Location: include/linux/netdevice.h:2105
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81742d9d)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/dev.c (ffffffff8188fd16)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/dst.c (ffffffff8189f3fb)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (ffffffff818a2945)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff818a6165)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff818b4f55)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffffffff818bd4e4)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (ffffffff818be661)
Location: include/linux/netdevice.h:2105
Inline: True
```
```
In net/core/fib_rules.c (ffffffff818c0194)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/sched/sch_api.c (ffffffff818d0675)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff818d4a77)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff818d64db)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818d9932)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffffffff818e0097)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff818e7625)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff818e85be)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff818e9ee9)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff818ee8d5)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911f00)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915adc)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81919fd7)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8191fccf)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff81921778)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81925042)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81927fe4)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_unregister
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff8192d6ba)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:__ip_mc_inc_group
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81932531)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff819352d0)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffff8193b525)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193bbec)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8193fcd5)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/xfrm4_input.c (ffffffff81949465)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff819498dd)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194a4a8)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81955703)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81956a51)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff819582ef)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff8195fa69)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81962365)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81964ba8)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81969014)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff81974d68)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff819804d3)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819852e9)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81988aa5)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff8198abcd)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff8198c067)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8199079f)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994e51)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff819975fb)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff8199b446)
Location: include/linux/netdevice.h:2105
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819a0736)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a11c3)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1bf5)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffff819a45f5)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a72e4)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819a8af5)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9b2c)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff819aafff)
Location: include/linux/netdevice.h:2105
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819b0e15)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffffffff819b5fff)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff819b6a0a)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bba6d)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff819c230d)
Location: include/linux/netdevice.h:2105
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
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
In kernel/bpf/offload.c (ffffffff811df0ae)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffffffff8141a2eb)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffffffff81421e56)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff81757605)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff81761df9)
Location: include/linux/netdevice.h:2170
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817675e1)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffff818a986e)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818b067a)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/dst.c (ffffffff818c1dbb)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (ffffffff818c5b55)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff818c97c5)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff818d8ed8)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffffffff818e48b4)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (ffffffff818e5a41)
Location: include/linux/netdevice.h:2170
Inline: True
```
```
In net/core/fib_rules.c (ffffffff818e90e4)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/sched/sch_api.c (ffffffff818fb860)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff818ff437)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/af_netlink.c (ffffffff81906382)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffffffff8190cc07)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff819144d5)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff81915b15)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff81917316)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8191c06d)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819406c9)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194428c)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81948844)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8194e93f)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff81950588)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81953e52)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81957244)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_unregister
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff8195cb5a)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81961d91)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81964cd0)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffff8196b215)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196ba57)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8196f575)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819796f2)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b12a)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b59a)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c468)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a313)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b6bd)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff8198cd1f)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff819946d1)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81997338)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8199a006)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff8199e8f4)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff819aa9a8)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff819b6ab3)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bba69)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff819bf405)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff819c149b)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff819c2aee)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c6eec)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb734)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff819cdecb)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d1d7a)
Location: include/linux/netdevice.h:2170
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d730a)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7ee8)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8825)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffff819db105)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dde3b)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819df625)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e064c)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff819e1b1f)
Location: include/linux/netdevice.h:2170
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e6205)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffffffff819ed2bf)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff819edcca)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f2cdd)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff819f986d)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a0424b)
Location: include/linux/netdevice.h:2170
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
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
In kernel/bpf/offload.c (ffffffff811f4a2e)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffffffff81447d96)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffffffff8144fa4f)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff81793dc5)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff817a2313)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a4e46)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffff818f5595)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818fd3d7)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/neighbour.c (ffffffff81911ba5)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff819167a5)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff819270ac)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffffffff81933ef4)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (ffffffff819352a1)
Location: include/linux/netdevice.h:2161
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81938b14)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff8194316b)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ethernet/eth.c (ffffffff81955965)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_api.c (ffffffff8195b1bf)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff8195fc05)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/af_netlink.c (ffffffff81967627)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffffffff8196e6f9)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff81976935)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff819780a4)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff81979246)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8197e390)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4c06)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a885c)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff819acee4)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819b311f)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff819b4e39)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff819b876d)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff819bbc84)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_unregister
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff819c185a)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff819c6af1)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff819caa23)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffff819d1ee5)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d276a)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff819d56cb)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffff819d8cb5)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e31f2)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e4634)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4ad0)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e5788)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4583)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6bdd)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff819f8319)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff81a002d8)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81a03313)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a05f59)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81a0aa24)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff81a175e8)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff81a25532)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a2a6a9)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a2e055)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a30279)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff81a31900)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a361ad)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a1c1)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81a3cae3)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a40b54)
Location: include/linux/netdevice.h:2161
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a463eb)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46ed9)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a47085)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffff81a49d85)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c990)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e1b5)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f2ad)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81a508df)
Location: include/linux/netdevice.h:2161
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a55c75)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffffffff81a5c4ab)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff81a5cf0a)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a6204d)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81a68dbd)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a734ed)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff81a73b55)
Location: include/linux/netdevice.h:2161
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/offload.c (ffffffff81201a3e)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffffffff81461926)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffffffff814698bf)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff817b78f5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff817c44a3)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c8f46)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffff8192748a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff8192f9be)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/neighbour.c (ffffffff81944215)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff81948df5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff8195974c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffffffff81966a14)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (ffffffff81968061)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/core/fib_rules.c (ffffffff8196b9d4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff81978250)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ethernet/eth.c (ffffffff8198be05)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_api.c (ffffffff8199181f)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81996c65)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/af_netlink.c (ffffffff8199e0b7)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffffffff819a5139)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff819ad355)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff819aea14)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff819afbb6)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819b4d40)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db906)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df52c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff819e3bb4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819e9e9f)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff819ebb69)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff819ef46d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff819f2984)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_unregister
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff819f83fa)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff819fd6a1)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01613)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffff81a08a55)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a0916a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81a0c237)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffff81a0fa15)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a1a1d9)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b644)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1baf0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c7b8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b223)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d84d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2ef74)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff81a36ebb)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81a39ee3)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a3cac9)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81a416d4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff81a4e238)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff81a5bfb2)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a611f9)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a64bc5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a66dc9)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff81a68450)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a6cccd)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70d62)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81a73763)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a777d4)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a7cfdb)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7da89)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7dc35)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffff81a80945)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83560)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a84e15)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a85f3d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81a874ff)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8d155)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffffffff81a930d8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff81a93b1a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a98c2d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81a9f71d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa9cdd)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff81aaa255)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/offload.c (ffffffff8122916e)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffffffff814b4f2d)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffffffff814bda5f)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff8187ea15)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff8188f7f1)
Location: include/linux/netdevice.h:2259
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8189357b)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffff819fb699)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a04b21)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/neighbour.c (ffffffff81a14285)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff81a219ef)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81a2d0cc)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffffffff81a3a144)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
```
```
In net/core/net-procfs.c (ffffffff81a3b841)
Location: include/linux/netdevice.h:2259
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81a3fac4)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff81a4cd5e)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ethernet/eth.c (ffffffff81a63895)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_api.c (ffffffff81a69601)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81a6f1c5)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/netlink/af_netlink.c (ffffffff81a76d84)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ethtool/netlink.c (ffffffff81a86615)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/netfilter/core.c (ffffffff81a8e3e9)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff81a970f5)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff81a9889d)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff81a99a86)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a9ef37)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac89da)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc66a)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics_req
  - net/ipv4/tcp_metrics.c:tcpm_new
```
```
In net/ipv4/raw.c (ffffffff81ad1445)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ad7a7d)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff81ad9469)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81add3bd)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81adea6b)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81ae4f8d)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_rejoin_groups
  - net/ipv4/igmp.c:ip_mc_rejoin_groups
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_add_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81aec091)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81af063a)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffff81af8295)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8bfa)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81afcd47)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffff81b032d5)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0b869)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c6e1)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0db78)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d8f5)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2024d)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21948)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff81b2c14f)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f6ca)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
```
```
In net/ipv6/ip6_input.c (ffffffff81b32169)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81b382d5)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_ifa_notify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:sit_add_v4_addrs
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81b44003)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff81b55d62)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81b5a64c)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b5d505)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b5f856)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff81b625ce)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_rejoin_groups
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/reassembly.c (ffffffff81b66252)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a56a)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81b6bf52)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b71af6)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b77987)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b782da)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78765)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b7950d)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/proc.c (ffffffff81b7b5c5)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e318)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fe95)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80f5d)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81b82b0f)
Location: include/linux/netdevice.h:2259
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b89775)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffffffff81b8e3e9)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff81b8f07a)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b9494d)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81b9b42d)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5edd)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff81ba6505)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/offload.c (ffffffff81230cfe)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffffffff814d2bc5)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffffffff814db4bf)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff8188cf95)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff8189db6f)
Location: include/linux/netdevice.h:2346
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a186b)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffff819fb29e)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a05141)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/neighbour.c (ffffffff81a14595)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff81a21e2f)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81a2ee55)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/net-sysfs.c (ffffffff81a3c6c4)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
```
```
In net/core/net-procfs.c (ffffffff81a3df41)
Location: include/linux/netdevice.h:2346
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81a427c4)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff81a52a20)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff81a66126)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/ethernet/eth.c (ffffffff81a6b9f5)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_frag.c (ffffffff81a6fa7e)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
```
In net/sched/sch_api.c (ffffffff81a71eb1)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81a77ba5)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/netlink/af_netlink.c (ffffffff81a7fb04)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ethtool/netlink.c (ffffffff81a8ff25)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/netfilter/core.c (ffffffff81a985e8)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff81aa11e5)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff81aa282d)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff81aa39d6)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81aa8e77)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad497a)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad863a)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics_req
  - net/ipv4/tcp_metrics.c:tcpm_new
```
```
In net/ipv4/raw.c (ffffffff81add4c5)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ae40cd)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5b4d)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81ae5ec9)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81aea10d)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81aeb86b)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81af1e5d)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:ip_mc_rejoin_groups
  - net/ipv4/igmp.c:ip_mc_rejoin_groups
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_add_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81af8f91)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd53e)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81b007f5)
Location: include/linux/netdevice.h:2346
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81b050f5)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b059ca)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81b0ab37)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffff81b11435)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b19bdd)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1aa01)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1bd88)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c1c5)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2eb8d)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30318)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff81b3ab70)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e11e)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
```
```
In net/ipv6/ip6_input.c (ffffffff81b40d89)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81b47005)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_ifa_notify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:sit_add_v4_addrs
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81b53103)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff81b64372)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81b68d4c)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b6bd03)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b6dff6)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff81b7133e)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_rejoin_groups
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/reassembly.c (ffffffff81b749d2)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b7903f)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81b7a9c2)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b8096c)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b86907)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b8723b)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b876d5)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b884a4)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/proc.c (ffffffff81b8a605)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d32a)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b8eb23)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b9077d)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81b92190)
Location: include/linux/netdevice.h:2346
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b99285)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffffffff81b9e089)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff81b9ecda)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba458d)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81bab13d)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb53bd)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff81bb6d65)
Location: include/linux/netdevice.h:2346
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/offload.c (ffffffff81234e9e)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffffffff814d9125)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffffffff814e1e3f)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff8186f8e5)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff81880aa5)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81883eed)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffff819e14f2)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819ed3d3)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/neighbour.c (ffffffff819faf25)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff81a09164)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81a16405)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_check_mtu
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/net-sysfs.c (ffffffff81a234d4)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:ifalias_store
```
```
In net/core/net-procfs.c (ffffffff81a25011)
Location: include/linux/netdevice.h:2410
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81a27404)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff81a3819c)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff81a460ce)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/ethernet/eth.c (ffffffff81a54185)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_frag.c (ffffffff81a5836e)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
```
In net/sched/sch_api.c (ffffffff81a5a737)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81a63605)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/netlink/af_netlink.c (ffffffff81a68a8d)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ethtool/netlink.c (ffffffff81a79655)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/netfilter/core.c (ffffffff81a83938)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff81a8c245)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff81a8d90d)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ea97)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a93f68)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfa30)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac39e1)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81ac83bd)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81acf2bd)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0e3d)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81ad11a9)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81ad5876)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81ad6ecb)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81ade5da)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae4751)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8d43)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/fib_trie.c (ffffffff81aebe7c)
Location: include/linux/netdevice.h:2410
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81af0955)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af124a)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81af83c7)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffff81aff065)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0766d)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b086b1)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b09a78)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19e25)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c942)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e198)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff81b28850)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c8b4)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b2eca9)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81b34db5)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:sit_add_v4_addrs
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81b40a93)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff81b52642)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81b56de0)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b5a015)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b5c3bf)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff81b5d16d)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:mld_mca_work
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/reassembly.c (ffffffff81b634f6)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67b89)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81b6940c)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f589)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b755cb)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b75f07)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b76385)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b771d4)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/proc.c (ffffffff81b79455)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c1df)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7dc13)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7f9b5)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81b81460)
Location: include/linux/netdevice.h:2410
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b88325)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffffffff81b8d189)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff81b8ddda)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b9319d)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81b9a2cd)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba43bd)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff81ba5c85)
Location: include/linux/netdevice.h:2410
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/offload.c (ffffffff8126efce)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffffffff81532266)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffffffff8153ae3f)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff818ffe55)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff819123ba)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81915883)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffff81a91932)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a9e5f3)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/neighbour.c (ffffffff81aacb65)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff81abb634)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81accc99)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_check_mtu
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/net-sysfs.c (ffffffff81ad7ad4)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:ifalias_store
```
```
In net/core/net-procfs.c (ffffffff81ad99ee)
Location: include/linux/netdevice.h:2430
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81adc196)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff81aee005)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff81b00e64)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/ethernet/eth.c (ffffffff81b0ce95)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_frag.c (ffffffff81b1134e)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
```
In net/sched/sch_api.c (ffffffff81b13897)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81b1c975)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/netlink/af_netlink.c (ffffffff81b2201c)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ethtool/netlink.c (ffffffff81b339d5)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/netfilter/core.c (ffffffff81b3d6cd)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff81b47215)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff81b48add)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff81b49c9b)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81b4f639)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d59c)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b81efb)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81b86c2d)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81b8dcdd)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f85a)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81b8fbc9)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81b94736)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81b9590b)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81b9daaa)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba4081)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8d68)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:ip_fib_check_default
```
```
In net/ipv4/fib_trie.c (ffffffff81bac09c)
Location: include/linux/netdevice.h:2430
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81bb07c5)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb145a)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81bb9167)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffff81bc2245)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bca56d)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb5c1)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcca38)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde445)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be12b4)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2c88)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff81bee81c)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81bf29c2)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4fd9)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81bfb4a5)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_v4_addrs
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81c070c3)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff81c19b52)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81c1d000)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81c21685)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81c23af4)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff81c2478a)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:mld_mca_work
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/reassembly.c (ffffffff81c2afb6)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f7d9)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81c30e3c)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/udp_offload.c (ffffffff81c37646)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff81c38f5b)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81c3ff6c)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c4097c)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c40df5)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81c41c74)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/proc.c (ffffffff81c440b5)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c479a5)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81c493c4)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b255)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bf87)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/output_core.c (ffffffff81c4d480)
Location: include/linux/netdevice.h:2430
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c54435)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffffffff81c5954b)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff81c5a24a)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f93d)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81c6793d)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c71f4d)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff81c742f5)
Location: include/linux/netdevice.h:2430
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/offload.c (ffffffff812bdf2e)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/netif.c (ffffffff815d2599)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff81a517c5)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff81a6539b)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6af61)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffff81c07afb)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81c173da)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/neighbour.c (ffffffff81c25b55)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/rtnetlink.c (ffffffff81c35ea8)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff81c49979)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_xdp_check_mtu
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/net-sysfs.c (ffffffff81c58844)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
```
```
In net/core/net-procfs.c (ffffffff81c5ae0a)
Location: include/linux/netdevice.h:2508
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81c5d5f6)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff81c70e40)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff81c80531)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/ethernet/eth.c (ffffffff81c937af)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_frag.c (ffffffff81c9843a)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
```
In net/sched/sch_api.c (ffffffff81c9a2a7)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81ca0b95)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/netlink/af_netlink.c (ffffffff81caac8a)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ethtool/netlink.c (ffffffff81cbf0e5)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/netfilter/core.c (ffffffff81cc9c81)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
  - net/netfilter/core.c:nf_hook_entry_head
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff81cd4325)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff81cd5ef0)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff81cd7207)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81cdcfd6)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d599)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d123a7)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81d17830)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81d1ee0d)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81d20b5b)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81d20f28)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81d25ff6)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/devinet.c (ffffffff81d2760d)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/igmp.c (ffffffff81d2fcda)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81d36991)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3b7c7)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:ip_fib_check_default
```
```
In net/ipv4/fib_trie.c (ffffffff81d3eefa)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_lookup_good_nhc
```
```
In net/ipv4/ping.c (ffffffff81d43d75)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44b2a)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81d4d127)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffff81d52b55)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5fd17)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d6106d)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c1d7)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75265)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d781e4)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79de3)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff81d86d9f)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b573)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81d8de27)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81d94c15)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_v4_addrs
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81da1753)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81db6019)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81dbbb50)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81dbe535)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81dc0a17)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff81dc192a)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81dc8266)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd685)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81dcec5f)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/udp_offload.c (ffffffff81dd51dd)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff81dd6ece)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81dde55c)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddee92)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf535)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81de0533)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/proc.c (ffffffff81de3005)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6dc6)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81de8b65)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deabb6)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81ded9f4)
Location: include/linux/netdevice.h:2508
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df2ae8)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:nf_hook_direct_egress
```
```
In net/wireless/wext-core.c (ffffffff81dface1)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff81dfbb4a)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e011ad)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81e0af60)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15ad7)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff81e17325)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mctp/device.c (ffffffff81e38351)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
  - net/mctp/device.c:mctp_addr_notify
```
```
In net/mctp/route.c (ffffffff81e3aa55)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_route_input
```
```
In net/mctp/neigh.c (ffffffff81e3b5ac)
Location: include/linux/netdevice.h:2508
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
  - net/mctp/neigh.c:mctp_rtm_newneigh
  - net/mctp/neigh.c:mctp_neigh_remove_dev
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
In kernel/bpf/offload.c (ffffffff813215ae)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/netif.c (ffffffff81680499)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff81bda8f5)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff81bf069b)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfdd63)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffff81db75ac)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81dc83da)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/neighbour.c (ffffffff81dd7da5)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/rtnetlink.c (ffffffff81de946f)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81dea6fc)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/filter.c (ffffffff81dfeba9)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_xdp_check_mtu
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/net-sysfs.c (ffffffff81e0e704)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
```
```
In net/core/net-procfs.c (ffffffff81e1104a)
Location: include/linux/netdevice.h:2535
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e13dc6)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff81e28ec0)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/devlink.c (ffffffff81e3e3bb)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_netdevice_event
  - net/core/devlink.c:devlink_netdevice_event
```
```
In net/ethernet/eth.c (ffffffff81e4eecf)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_frag.c (ffffffff81e5444a)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
```
In net/sched/sch_api.c (ffffffff81e56627)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81e5cbd5)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/netlink/af_netlink.c (ffffffff81e67e30)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ethtool/netlink.c (ffffffff81e7dc75)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/netfilter/core.c (ffffffff81e8989a)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
  - net/netfilter/core.c:nf_hook_entry_head
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff81e94595)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff81e963b0)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff81e977d7)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81e9da46)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2a2b)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed81a7)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81ede0f0)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ee63e5)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_rcv
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7d9f)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81ee82a8)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_accept
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81eed826)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/devinet.c (ffffffff81eeef9d)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/igmp.c (ffffffff81ef7dca)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81eff021)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81f04197)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:ip_fib_check_default
```
```
In net/ipv4/fib_trie.c (ffffffff81f07ada)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_lookup_good_nhc
```
```
In net/ipv4/ping.c (ffffffff81f0cdd5)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0ddca)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81f16a07)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffff81f1cea5)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f2a437)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2b95d)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f37547)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41825)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44a94)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46c34)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff81f5495f)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81f59583)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bf97)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81f633d5)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_v4_addrs
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81f70ab3)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81f85c79)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81f8bc05)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_rcv
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81f8e8be)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81f90f72)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff81f9223a)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81f98ff6)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e6d5)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81f9ff8f)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/udp_offload.c (ffffffff81fa68c0)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff81fa888e)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81fb07dc)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb0f52)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb17e5)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81fb28c3)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/proc.c (ffffffff81fb5625)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9c46)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81fbba85)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe776)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81fc17c4)
Location: include/linux/netdevice.h:2535
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc6ed8)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:nf_hook_direct_egress
```
```
In net/wireless/wext-core.c (ffffffff81fcf517)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff81fd041a)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd5fdd)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81fe0830)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81feca87)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff81fedd75)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mctp/device.c (ffffffff820115b1)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
  - net/mctp/device.c:mctp_addr_notify
```
```
In net/mctp/route.c (ffffffff82014025)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_route_input
```
```
In net/mctp/neigh.c (ffffffff82014c7c)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_neigh_remove_dev
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
In kernel/bpf/offload.c (ffffffff8135110e)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/netif.c (ffffffff816b8579)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff81c31395)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff81c48c59)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c633a2)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In drivers/net/net_failover.c (ffffffff81c6f538)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_create
```
```
In net/core/flow_dissector.c (ffffffff81e27c71)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81e3878f)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/neighbour.c (ffffffff81e48b15)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/rtnetlink.c (ffffffff81e5accf)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81e5bedc)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/filter.c (ffffffff81e70165)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_tc_sk_lookup_udp
  - net/core/filter.c:bpf_tc_sk_lookup_tcp
  - net/core/filter.c:bpf_tc_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_xdp_check_mtu
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/netdev-genl.c (ffffffff81e7cf25)
Location: include/linux/netdevice.h:2588
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81e81b44)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
```
```
In net/core/net-procfs.c (ffffffff81e8495a)
Location: include/linux/netdevice.h:2588
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e876f6)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff81e9e4f4)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/failover.c (ffffffff81ea061a)
Location: include/linux/netdevice.h:2588
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81eaa56f)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_frag.c (ffffffff81eafcea)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
```
In net/sched/sch_api.c (ffffffff81eb2c66)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81eb9785)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/netlink/af_netlink.c (ffffffff81ec3c88)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ethtool/netlink.c (ffffffff81eda235)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/netfilter/core.c (ffffffff81ee7744)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
  - net/netfilter/core.c:nf_hook_entry_head
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff81ef2d65)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff81ef4be0)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6007)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81efc1c7)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f3170b)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f3729a)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81f3d3f0)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81f45be5)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_rcv
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81f4762a)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81f47b7a)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_accept
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81f4d1e6)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/devinet.c (ffffffff81f4e95d)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/igmp.c (ffffffff81f5785a)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5eab1)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63b77)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:ip_fib_check_default
```
```
In net/ipv4/fib_trie.c (ffffffff81f675ba)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_lookup_good_nhc
```
```
In net/ipv4/ping.c (ffffffff81f6ca45)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6da7a)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81f766cd)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffff81f7c985)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8a007)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b7b7)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f96f1a)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa10c5)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa4274)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6570)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff81fb436f)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9233)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81fbbd47)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81fc3395)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_v4_addrs
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81fd0ba3)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ndisc.c (ffffffff81fe6039)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff81fec3a5)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_rcv
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81fef08a)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81ff1862)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff81ff2baa)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81ff99c6)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81fff195)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff82000a6f)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/udp_offload.c (ffffffff82007131)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff8200921e)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff82010e8c)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff82011602)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff82011e85)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff82012fd8)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/proc.c (ffffffff82015d45)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a20d)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201c385)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f616)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff82022744)
Location: include/linux/netdevice.h:2588
Inline: True
```
```
In net/packet/af_packet.c (ffffffff82027bf8)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:nf_hook_direct_egress
```
```
In net/devlink/leftover.c (ffffffff820419cf)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_port_netdevice_event
  - net/devlink/leftover.c:devlink_port_netdevice_event
```
```
In net/wireless/wext-core.c (ffffffff8204b193)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff8204beda)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82051c9d)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff8205cbe0)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068d27)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff82069ed5)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mctp/device.c (ffffffff8208e391)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
  - net/mctp/device.c:mctp_addr_notify
```
```
In net/mctp/route.c (ffffffff82090ea5)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_route_input
```
```
In net/mctp/neigh.c (ffffffff82091a9c)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_neigh_remove_dev
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
In kernel/bpf/offload.c (ffffffff8137856e)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/netif.c (ffffffff816f4fa9)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff81ce4225)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/netkit.c (ffffffff81ce4845)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_get_link_net
  - drivers/net/netkit.c:netkit_get_link_net
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
```
```
In drivers/net/tun.c (ffffffff81cfe5b9)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d19dc2)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In drivers/net/net_failover.c (ffffffff81d23de8)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_create
```
```
In net/core/flow_dissector.c (ffffffff81ee5c21)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81ef68ad)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:__dev_forward_skb2
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/neighbour.c (ffffffff81f076d5)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/rtnetlink.c (ffffffff81f1a08f)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_set_master
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81f1b2a2)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/filter.c (ffffffff81f2a3e5)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_tc_sk_lookup_udp
  - net/core/filter.c:bpf_tc_sk_lookup_tcp
  - net/core/filter.c:bpf_tc_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_xdp_check_mtu
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/netdev-genl.c (ffffffff81f3d6ad)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_genl_dev_notify
  - net/core/netdev-genl.c:netdev_genl_dev_notify
```
```
In net/core/net-sysfs.c (ffffffff81f42b24)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
```
```
In net/core/page_pool_user.c (ffffffff81f45639)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_netdevice_event
  - net/core/page_pool_user.c:netdev_nl_page_pool_event
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_do
```
```
In net/core/net-procfs.c (ffffffff81f4690a)
Location: include/linux/netdevice.h:2647
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81f49706)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff81f60c6d)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/failover.c (ffffffff81f62dba)
Location: include/linux/netdevice.h:2647
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81f6d01f)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_frag.c (ffffffff81f7275a)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit_hook
```
```
In net/sched/sch_api.c (ffffffff81f75776)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81f7c913)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
```
In net/netlink/af_netlink.c (ffffffff81f87048)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ethtool/netlink.c (ffffffff81f9dfc5)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_multicast
```
```
In net/netfilter/core.c (ffffffff81fab554)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
  - net/netfilter/core.c:nf_hook_entry_head
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff81fb6cf5)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff81fb8b80)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff81fb9f97)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fc0127)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff78fc)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffd36a)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcpm_new
```
```
In net/ipv4/raw.c (ffffffff82003550)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8200bd35)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_rcv
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8200d76a)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff8200dcba)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_accept
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff820132f6)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_socket_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/devinet.c (ffffffff82014a9d)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/igmp.c (ffffffff8201dcea)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff82025081)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff8202a147)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:fib_rebalance
  - net/ipv4/fib_semantics.c:ip_fib_check_default
```
```
In net/ipv4/fib_trie.c (ffffffff8202db9a)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_lookup_good_nhc
```
```
In net/ipv4/ping.c (ffffffff82033195)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820341ca)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff8203ce9d)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffff82043085)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82051767)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff820530b7)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff8206429a)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e3e5)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff820715a4)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/xfrm/xfrm_device.c (ffffffff82073860)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/xfrm/xfrm_state_bpf.c (ffffffff82075df5)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/xfrm/xfrm_state_bpf.c:bpf_xdp_get_xfrm_state
```
```
In net/ipv6/anycast.c (ffffffff82081c1f)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff820867b3)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff82089177)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff82090955)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_v4_addrs
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff8209e493)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ndisc.c (ffffffff820b3e99)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_alloc_skb
```
```
In net/ipv6/udp.c (ffffffff820b9fb5)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_rcv
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff820bcc59)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff820bf461)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff820c083a)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff820c7636)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cdea5)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:__inet6_lookup_skb
```
```
In net/ipv6/exthdrs.c (ffffffff820cf8af)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/udp_offload.c (ffffffff820d5f91)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff820d81be)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff820dfe1c)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e09b6)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e0ff5)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff820e2138)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/proc.c (ffffffff820e4e95)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e91da)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820eb355)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee746)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff820f1864)
Location: include/linux/netdevice.h:2647
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820f7458)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:nf_hook_direct_egress
```
```
In net/devlink/port.c (ffffffff8210821f)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_netdevice_event
  - net/devlink/port.c:devlink_port_netdevice_event
```
```
In net/wireless/wext-core.c (ffffffff8211d613)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff8211e35a)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8212447d)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff8212f7f0)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213bfa7)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff8213d335)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mctp/device.c (ffffffff82164884)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
  - net/mctp/device.c:mctp_addr_notify
```
```
In net/mctp/route.c (ffffffff821673c5)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_remove_dev
  - net/mctp/route.c:mctp_route_remove
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_route_input
```
```
In net/mctp/neigh.c (ffffffff8216803c)
Location: include/linux/netdevice.h:2647
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_neigh_remove_dev
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
In kernel/bpf/offload.c (ffff800010289978)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffff80001054f058)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffff800010557e34)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffff8000109cff58)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffff8000109df640)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a03368)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffff800010bc39a8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffff800010bccec0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/neighbour.c (ffff800010be4104)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffff800010bea800)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffff800010bfae8c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffff800010c0c180)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (ffff800010c0de0c)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/core/fib_rules.c (ffff800010c12044)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffff800010c1eaac)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ethernet/eth.c (ffff800010c36eb0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_api.c (ffff800010c3db4c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffff800010c43d84)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/af_netlink.c (ffff800010c4b5f4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffff800010c54684)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffff800010c5d3b0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffff800010c5ef94)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffff800010c60278)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffff800010c65654)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ec6c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92e3c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffff800010c9859c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffff800010c9f6bc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffff800010ca154c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffff800010ca51f4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffff800010ca8c70)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_unregister
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffff800010cb0020)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffff800010cb5898)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9c44)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffff800010cc1c8c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc24bc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffff800010cc55fc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffff800010ccca20)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd60b4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd78c0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7d90)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffff800010cda82c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9ab4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec5e0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffff800010cedcb0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffff800010cf7c40)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffff800010cfae84)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffff800010cfde2c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffff800010d03140)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffff800010d0ead0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffff800010d2135c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d2446c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffff800010d2aafc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffff800010d2cd2c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffff800010d2fe44)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffff800010d35890)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d391e8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffff800010d3c214)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffff800010d40e0c)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d47bf4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48c74)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffff800010d48f48)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffff800010d4c160)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f348)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffff800010d50ef0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffff800010d52818)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffff800010d53dec)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d5ad3c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffff800010d60f08)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffff800010d61da0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68430)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffff800010d70c64)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d9ac)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffff800010d7ed5c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/offload.c (c04b91d8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (c0708a38)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (c070cd0c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (c0ab8160)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (c0ac3ad8)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (c0ade1b0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (c0cdeca4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (c0ce88d0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/neighbour.c (c0cfe5a0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get_next
  - net/core/neighbour.c:neigh_get_first
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (c0d03614)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (c0d14864)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_slow
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (c0d246c0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (c0d25f60)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/core/fib_rules.c (c0d29d34)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (c0d36b04)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ethernet/eth.c (c0d49818)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_api.c (c0d4f614)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (c0d5491c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_cmd
  - net/sched/cls_api.c:tc_indr_block_call
```
```
In net/netlink/af_netlink.c (c0d5c000)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (c0d6438c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (c0d6cb64)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (c0d6e58c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (c0d6fb2c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c0d7510c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (c0d9dbc4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (c0da1818)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (c0da63e4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0dac9c8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (c0dae420)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (c0db1b18)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (c0db540c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_unregister
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (c0dbb9dc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mcf_get_next
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (c0dc11fc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (c0dc53f0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (c0dcd40c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (c0dcdd88)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (c0dd102c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (c0dd7018)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/cipso_ipv4.c (c0ddff58)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (c0de13d0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (c0de1854)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (c0de25e0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (c0df1bb0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df4508)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (c0df5f08)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (c0dfd5c0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_get_next
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (c0e01788)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c0e058b8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (c0e0a5d8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (c0e16558)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (c0e25d4c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c0e2b2bc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (c0e2ea48)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c0e30d88)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (c0e31334)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_get_next
  - net/ipv6/mcast.c:igmp6_mc_get_next
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c0e37a94)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c0e3bd30)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (c0e3f424)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (c0e43810)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e496d8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (c0e49f04)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (c0e4a380)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (c0e4d3a0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (c0e500a0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c0e51a48)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (c0e52cdc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (c0e545a8)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/packet/af_packet.c (c0e57a44)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (c0e605d4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (c0e61180)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (c0e660bc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (c0e6dcc0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (c0e784e4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (c0e78944)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/offload.c (c000000000335068)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (c0000000006b0460)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (c0000000006b5e60)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (c000000000a8efcc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (c000000000aa4610)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa93f0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (c000000000c9dbdc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (c000000000caac58)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/neighbour.c (c000000000cc75a4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get_next
  - net/core/neighbour.c:neigh_get_first
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (c000000000ccd908)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (c000000000ce31ec)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (c000000000cf7444)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (c000000000cf9708)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/core/fib_rules.c (c000000000cfeecc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (c000000000d10c58)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ethernet/eth.c (c000000000d2ef30)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_api.c (c000000000d37664)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (c000000000d3f0fc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/af_netlink.c (c000000000d497f8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (c000000000d54530)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (c000000000d5fbe8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (c000000000d61b34)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (c000000000d6317c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c000000000d69cec)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d7d0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (c000000000da3108)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (c000000000da9c5c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c000000000db2180)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (c000000000db46c8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (c000000000db9000)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (c000000000dbdd64)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_unregister
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (c000000000dc6008)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (c000000000dcd430)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (c000000000dd2ce0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (c000000000ddd21c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dddbb8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (c000000000de1c08)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (c000000000de7614)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/cipso_ipv4.c (c000000000df5ab4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (c000000000df778c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (c000000000df7e20)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (c000000000df9aa0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (c000000000e0d408)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e107b8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (c000000000e12890)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (c000000000e1e654)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (c000000000e22320)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c000000000e260d8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (c000000000e2c7e4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (c000000000e3c644)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (c000000000e50780)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c000000000e56cdc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (c000000000e5bd54)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c000000000e5e818)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (c000000000e5f2bc)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_get_next
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c000000000e67950)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c7d0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (c000000000e6fde4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (c000000000e755b8)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e7d06c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7dc84)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e344)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (c000000000e82710)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86c70)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c000000000e88dd8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (c000000000e8af00)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (c000000000e8c730)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/packet/af_packet.c (c000000000e9218c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (c000000000e9c304)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (c000000000e9d184)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea3f0c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (c000000000eaf454)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebd4e8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (c000000000ebf130)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/offload.c (ffffffe0001bdc04)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffffffe0003a9022)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffffffe0003af722)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffe00061cb90)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffe0006290b2)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062d71c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffe00075046a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffe0007575d6)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/neighbour.c (ffffffe00076aa68)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_get_next
  - net/core/neighbour.c:neigh_get_first
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffe00076e382)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffe00077ca16)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffffffe00078953e)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:ifalias_store
```
```
In net/core/net-procfs.c (ffffffe00078aa06)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/core/fib_rules.c (ffffffe00078e080)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffe0007986c4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ethernet/eth.c (ffffffe0007a880c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_api.c (ffffffe0007ade6a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffe0007b2248)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/af_netlink.c (ffffffe0007b8d2c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffffffe0007becf4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffe0007c6074)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffe0007c74c2)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffe0007c8526)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffe0007cce5e)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eef46)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f25e4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffe0007f6972)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_rcv
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffe0007fc1fa)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffe0007fdc78)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffe000800b40)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffe000803994)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_unregister
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffe000809100)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffe00080d14e)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffe000810734)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffe0008172e6)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe0008178f4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffe000819432)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffe00081e2a2)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/cipso_ipv4.c (ffffffe000826bfe)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffe000827fa2)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffe00082836c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffe000828f08)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffe00083793e)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000839cde)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b32c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffe000842ea6)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffe000845a1a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffe00084829c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffe00084c458)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffe000854584)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffe000863246)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffe000867fae)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffe00086b168)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffe00086cf6c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffe00086d5a4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_get_next
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffe000872d2e)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087656c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffe000878c32)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffe00087c5ec)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe00088189c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000882002)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffe00088248a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffe000884f0e)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887e64)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffe0008891b6)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a82c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffe00088b956)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/packet/af_packet.c (ffffffe000891054)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffffffe000895f7c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffe00089671e)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b79a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffe0008a1954)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab1d4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffe0008ab5e0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/offload.c (ffffffff811fa05e)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffffffff81459f06)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffffffff81461e9f)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff8177c3d5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff81788f83)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178da26)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffff818c748a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818cf9be)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/neighbour.c (ffffffff818e41e5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff818e8dc5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff818f971c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffffffff819069e4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (ffffffff81908031)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/core/fib_rules.c (ffffffff8190b9a4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff819180c0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ethernet/eth.c (ffffffff8192bc75)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_api.c (ffffffff8193168f)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81936ad5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/af_netlink.c (ffffffff8193df27)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffffffff81944fa9)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff8194d1c5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff8194e884)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff8194fa26)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81954bb0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b776)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197f39c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81983a24)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81989d0f)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff8198b999)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff8198f20d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81992724)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_unregister
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff8199819a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff8199d441)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff819a13b3)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffff819a87f5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8f0a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff819abfd7)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffff819af445)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b9869)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff819bacd4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb180)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbe48)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff819ca8b3)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819ccedd)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce604)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff819d654b)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff819d9573)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819dc159)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff819e0d64)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff819ed8c8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff819fb642)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a00889)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a04255)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a06459)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff81a07ae0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a0c35d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a103f2)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81a12df3)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a16e64)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a1c66b)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1d119)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d2c5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffff81a1ffd5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22bf0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a244a5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a255cd)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81a26b8f)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2c7e5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffffffff81a32768)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff81a331aa)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a37fbd)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81a3eaad)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a4906d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff81a495e5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/offload.c (ffffffff811ecdae)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffffffff8144a936)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffffffff814528cf)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff8175c185)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff817688d3)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/vxlan.c (ffffffff8176c318)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_exit_batch_net
  - drivers/net/vxlan.c:vxlan_netdevice_event
  - drivers/net/vxlan.c:vxlan_offload_rx_ports
  - drivers/net/vxlan.c:vxlan_fill_metadata_dst
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_fdb_parse
  - drivers/net/vxlan.c:__vxlan_fdb_notify
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817767f6)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffff818813ca)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81889ade)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/neighbour.c (ffffffff8189e025)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff818a2c05)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff818b354c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffffffff818c0814)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (ffffffff818c1e41)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/core/fib_rules.c (ffffffff818c5764)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff818d1e70)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ethernet/eth.c (ffffffff818e5a25)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_api.c (ffffffff818eb18f)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff818f05d5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/af_netlink.c (ffffffff818f7a27)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffffffff818fea99)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff81906cb5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff81908374)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff81909516)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8190e6a0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81935236)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938e5c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff8193d4e4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819437cf)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff81945459)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81948ccd)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff8194c1e4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_unregister
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81951c5a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81956f01)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff8195ae73)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffff819622b5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819629ca)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81965a97)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967244)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_init
  - net/ipv4/ip_tunnel.c:ip_tunnel_newlink
  - net/ipv4/ip_tunnel.c:ip_tunnel_delete_nets
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv4/ipmr.c (ffffffff8196ba75)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81976659)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977ac4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81977f70)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978c38)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff819876a3)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81989ccd)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b3e4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff8199330b)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81996333)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81998f19)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff8199db24)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff819aa688)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff819b8402)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bd649)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff819c1015)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff819c3219)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff819c48a0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c911d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd1b2)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff819cfbb3)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d3c24)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d942b)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9ed9)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da085)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffff819dcd95)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819df9b0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819e1265)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e238d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff819e394f)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/ipv6/ip6_udp_tunnel.c (ffffffff819e5b44)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_udp_tunnel.c:udp_tunnel6_xmit_skb
```
```
In net/packet/af_packet.c (ffffffff819e99d5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffffffff819ef958)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff819f028a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f4bdd)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff819fb69d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05c5d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff81a061d5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/offload.c (ffffffff811f7e2e)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffffffff81455fa6)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffffffff8145df3f)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff817ac775)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff817b9323)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bddc6)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffff8191848a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819209be)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/neighbour.c (ffffffff81935215)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff81939df5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff8194a74c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffffffff81957a14)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (ffffffff81959061)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/core/fib_rules.c (ffffffff8195c9d4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff81969250)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ethernet/eth.c (ffffffff8197ce05)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_api.c (ffffffff8198281f)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81987c65)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/af_netlink.c (ffffffff8198f0b7)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffffffff81996139)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999433)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_rcv_dev_event
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199f479)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/ipv4/route.c (ffffffff819b7995)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff819b9054)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff819ba1f6)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819bf380)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5f46)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9b6c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff819ee1f4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819f44df)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff819f61a9)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff819f9aad)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff819fcfc4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_unregister
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81a02a3a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81a07ce1)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0bc53)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffff81a13095)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a137aa)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81a16877)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffff81a19ce5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a242e9)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a25754)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25c00)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a268c8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35333)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a3795d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81a39084)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff81a40fcb)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81a43ff3)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a46bd9)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81a4b7e4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff81a58348)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff81a660c2)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a6b309)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a6ecd5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a70ed9)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff81a72560)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a76ddd)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7ae72)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d873)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a818e4)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a870eb)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a87b99)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a87d45)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffff81a8aa55)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d670)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ef25)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9004d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81a9273f)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a98395)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffffffff81a9e318)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff81a9ed5a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa3e6d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81aaa95d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4f1d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff81ab5495)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/offload.c (ffffffff812063ae)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In security/selinux/hooks.c (ffffffff81471296)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
```
```
In security/selinux/netif.c (ffffffff814756df)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/loopback.c (ffffffff817c6705)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_free
```
```
In drivers/net/tun.c (ffffffff817d4db7)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d85f6)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
```
In net/core/flow_dissector.c (ffffffff819394d1)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff8194274e)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/neighbour.c (ffffffff81956925)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_notify
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_lookup_nodev
```
```
In net/core/rtnetlink.c (ffffffff8195b625)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/filter.c (ffffffff8196c05c)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
```
In net/core/net-sysfs.c (ffffffff81979af4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:net_get_ownership
  - net/core/net-sysfs.c:net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/net-procfs.c (ffffffff8197b1d1)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/core/fib_rules.c (ffffffff8197ec14)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/lwt_bpf.c (ffffffff8198b630)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ethernet/eth.c (ffffffff8199f375)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_get_headlen
```
```
In net/sched/sch_api.c (ffffffff819a4d5f)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff819a9ec5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/af_netlink.c (ffffffff819b199f)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/core.c (ffffffff819b8d09)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entry_head
```
```
In net/ipv4/route.c (ffffffff819c1205)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ipv4_dst_check
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/ip_input.c (ffffffff819c2944)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_forward.c (ffffffff819c3ae6)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819c8d00)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efc06)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f392e)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff819f8254)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819fe69f)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/arp.c (ffffffff81a003a9)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/arp.c:parp_redo
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/arp.c:arp_ignore
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/icmp.c (ffffffff81a03d9d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/devinet.c (ffffffff81a07354)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_unregister
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:confirm_addr_indev
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/igmp.c (ffffffff81a0cf6a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_netdev_event
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_del1_src
  - net/ipv4/igmp.c:ip_mc_up
  - net/ipv4/igmp.c:ip_mc_init_dev
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/fib_frontend.c (ffffffff81a12421)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/fib_semantics.c (ffffffff81a16443)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/ping.c (ffffffff81a1da65)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e17a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81a212b7)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
```
In net/ipv4/ipmr.c (ffffffff81a24b05)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_device_event
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2f722)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30bd6)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a310a0)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31d78)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40c53)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a4331d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44ab4)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/anycast.c (ffffffff81a4cbd6)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81a4fc94)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a5294a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ipv6_list_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81a57754)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff81a644e3)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ndisc.c (ffffffff81a72683)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a77919)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a7b305)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a7d4e9)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
```
```
In net/ipv6/mcast.c (ffffffff81a7ebf2)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a833fd)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a876b2)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81a8a0c3)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e1e4)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a93cbb)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a947b8)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_get_saddr
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94975)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/proc.c (ffffffff81a976b5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_unregister_dev
  - net/ipv6/proc.c:snmp6_register_dev
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a360)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bca5)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d1b1)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81a9e818)
Location: include/linux/netdevice.h:2174
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa1988)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/wireless/wext-core.c (ffffffff81aaa518)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/wireless/wext-proc.c (ffffffff81aaaf5a)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aaf71d)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81ab6ccd)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_notify
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac12bd)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout
  - net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp
```
```
In net/xdp/xsk.c (ffffffff81ac1a85)
Location: include/linux/netdevice.h:2174
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
</details>
</li>
</ul>

## Differences
