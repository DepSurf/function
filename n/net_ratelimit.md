# Function: <code>net_ratelimit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff8172fc40)
Location: net/core/utils.c:40
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/socket.c:__sock_create
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:__neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:tc_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_pick_tx_queue
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff8172fc40-ffffffff8172fc5e: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff8179a390)
Location: net/core/utils.c:40
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:__neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:tc_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_pick_tx_queue
```
**Symbols:**

```
ffffffff8179a390-ffffffff8179a3ae: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff817c8130)
Location: net/core/utils.c:40
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:__neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_api.c:tc_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_pick_tx_queue
```
**Symbols:**

```
ffffffff817c8130-ffffffff817c814e: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff817e6a70)
Location: net/core/utils.c:42
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:__neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff817e6a70-ffffffff817e6a8e: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818619b0)
Location: net/core/utils.c:42
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:__neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff818619b0-ffffffff818619ce: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818ad5e0)
Location: net/core/utils.c:42
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:__neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff818ad5e0-ffffffff818ad5fe: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818d1840)
Location: net/core/utils.c:42
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:___neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff818d1840-ffffffff818d185e: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff8191eac0)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:___neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff8191eac0-ffffffff8191eade: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81950d50)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:___neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81950d50-ffffffff81950d6e: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81a21c80)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_extras
  - drivers/net/xen-netfront.c:xennet_get_extras
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_frags_skb
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_alloc
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:__tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:mld_process_v2
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_pick_tx_queue
```
**Symbols:**

```
ffffffff81a21c80-ffffffff81a21c9e: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81a22000)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_extras
  - drivers/net/xen-netfront.c:xennet_get_extras
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_frags_skb
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_alloc
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/cls_api.c:__tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:mld_process_v2
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_pick_tx_queue
```
**Symbols:**

```
ffffffff81a22000-ffffffff81a2201e: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81a09330)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_alloc
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/cls_api.c:__tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:mld_process_v2
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81a09330-ffffffff81a0934e: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81abb810)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_alloc
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/cls_api.c:__tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81abb810-ffffffff81abb82e: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81c36120)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_alloc
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/gro.c:napi_gro_frags
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/cls_api.c:__tcf_classify
  - net/sched/act_api.c:tcf_action_exec
  - net/sched/act_api.c:tcf_action_exec
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81c36120-ffffffff81c36146: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81de97c0)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_alloc
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/gro.c:napi_gro_frags
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/cls_api.c:__tcf_classify
  - net/sched/act_api.c:tcf_action_exec
  - net/sched/act_api.c:tcf_action_exec
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81de97c0-ffffffff81de97e6: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81e5afd0)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_alloc
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/gro.c:napi_gro_frags
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/cls_api.c:__tcf_classify
  - net/sched/act_api.c:tcf_action_exec
  - net/sched/act_api.c:tcf_action_exec
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_xmit
```
**Symbols:**

```
ffffffff81e5afd0-ffffffff81e5aff6: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81f1a390)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:pad_compress_skb
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_get_responses
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_partial_csum_set
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:neigh_alloc
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/gro.c:napi_gro_frags
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/cls_api.c:__tcf_classify
  - net/sched/act_api.c:tcf_action_exec
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_alloc_skb
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_xmit
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_copy_ip_options
```
**Symbols:**

```
ffffffff81f1a390-ffffffff81f1a3b6: net_ratelimit (STB_GLOBAL)
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
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffff800010bf2918)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/neighbour.c:___neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffff800010bf2918-ffff800010bf2944: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (c0d0b130)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_tx_timeout
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_start_xmit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_start_xmit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_stop
  - drivers/net/ethernet/ti/cpsw.c:cpsw_fill_rx_channels
  - drivers/net/ethernet/ti/cpsw.c:cpsw_fill_rx_channels
  - drivers/net/ethernet/ti/cpsw.c:cpsw_fill_rx_channels
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_update_channels_res
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_update_channels_res
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_ethtool_op_complete
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_ethtool_op_begin
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_set_coalesce
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:___neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
c0d0b130-c0d0b15c: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (c000000000cd77f0)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:___neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
c000000000cd77f0-c000000000cd7834: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffe000774352)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:___neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffe000774352-ffffffe000774384: net_ratelimit (STB_GLOBAL)
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
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818f0d20)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:___neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff818f0d20-ffffffff818f0d3e: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818aab60)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_snoop
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:___neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff818aab60-ffffffff818aab7e: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81941d50)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:___neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/netfilter/nfnetlink_queue.c:__nfqnl_enqueue_packet
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_alloc
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81941d50-ffffffff81941d6e: net_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int net_ratelimit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81963650)
Location: net/core/utils.c:38
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/socket.c:__sock_create
  - net/core/sock.c:sock_set_timeout
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:skb_warn_bad_offload
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:___neigh_create
  - net/core/rtnetlink.c:do_setlink
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/cls_api.c:tcf_classify
  - net/sched/ematch.c:__tcf_em_tree_match
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_check_oom
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_route_lookup
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81963650-ffffffff8196366e: net_ratelimit (STB_GLOBAL)
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
