# Function: <code>ipv6_hdr</code>

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
In security/lsm_audit.c (ffffffff81366272)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff817095da)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8173962e)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782d69)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ping.c (ffffffff817a2489)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff817b7fbc)
Location: include/linux/ipv6.h:77
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c4d2a)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff817c8b6c)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff817d6fba)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff817dea83)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff817e4990)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff817e6c35)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff817e772c)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff817ea12f)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff817edce8)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817eee4c)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_sequence
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f31ff)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (ffffffff817f4bd9)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/ip6mr.c (ffffffff817f8d28)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_get_route
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fc2c3)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff817fca75)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/ipv6.h:77
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd1ff)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
```
```
In net/ipv6/netfilter.c (ffffffff817fdbc1)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/ipv6.h:77
Inline: True
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:77
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff818002d8)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff818004c6)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff81800f0b)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff8180128e)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/udp_offload.c (ffffffff818015f3)
Location: include/linux/ipv6.h:77
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/mcast_snoop.c (ffffffff818025da)
Location: include/linux/ipv6.h:77
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:77
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
In security/lsm_audit.c (ffffffff8139c352)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8177157e)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff817a58e0)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817f039b)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ping.c (ffffffff81810552)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff818251cc)
Location: include/linux/ipv6.h:81
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8183514a)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81836227)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81841514)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff8184faff)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81852a7d)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff818545fa)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81856dcc)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81859673)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8185c693)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818603e0)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_sequence
```
```
In net/ipv6/exthdrs.c (ffffffff81862610)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff818643ca)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff8186695a)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8186b41f)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186bbc3)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff8186c395)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff8186c732)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186cc1b)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff8186d81c)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff8186ecc9)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff81870069)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:81
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81871946)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff81871d3f)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/ipv6/ip6_offload.c (ffffffff81872845)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872ace)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff818738dd)
Location: include/linux/ipv6.h:81
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (ffffffff8187de8e)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818822a9)
Location: include/linux/ipv6.h:81
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/lsm_audit.c (ffffffff813b2f02)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8179e69e)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff817d4350)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81820ddf)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ping.c (ffffffff81841a52)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81856b2c)
Location: include/linux/ipv6.h:87
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81866c84)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81867d37)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81873374)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81881a1f)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff8188477d)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81886323)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81888bcc)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8188b4a3)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8188e5a3)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892370)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_sequence
```
```
In net/ipv6/exthdrs.c (ffffffff818946a1)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81896ab8)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff8189905a)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8189e27f)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189ea20)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff8189f1a5)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff8189f542)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189fa0b)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff818a061c)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff818a1c19)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff818a2fd9)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a46d6)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a4ee0)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:87
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5ea6)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff818a62ad)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6e4c)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a70ee)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a7f5d)
Location: include/linux/ipv6.h:87
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (ffffffff818b273e)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b6b59)
Location: include/linux/ipv6.h:87
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/lsm_audit.c (ffffffff813c98d4)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff817bc2ee)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff817f36bf)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840f95)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ping.c (ffffffff818631aa)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff8187a4a8)
Location: include/linux/ipv6.h:90
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8188b352)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8188c546)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81897d43)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff818a7b37)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff818aa1f8)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff818aca7a)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff818af25c)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff818b1229)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff818b4be5)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b89cf)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff818baa82)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff818bd031)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff818bf279)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff818c483c)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c4fa2)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff818c5715)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/ipv6.h:90
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c5faa)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff818c6c61)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff818c81e3)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff818c95a9)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818caf73)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb926)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:90
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc927)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff818cccfd)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd712)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdb5e)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce7b9)
Location: include/linux/ipv6.h:90
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (ffffffff818d90ee)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dd439)
Location: include/linux/ipv6.h:90
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/lsm_audit.c (ffffffff813efd64)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818369be)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (ffffffff8186eaaf)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0b5d)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ping.c (ffffffff818e32da)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff818faf18)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8190c575)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8190d836)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff819190c3)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff8192a5e7)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff8192cc6c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff8192f2d7)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81931f6c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81933879)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81937955)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b881)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff8193da92)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81940151)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff81942394)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6mr.c (ffffffff81947adc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81948272)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff819489f5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948dbb)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff8194934e)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff8194a121)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff8194b793)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff8194cc49)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e8b9)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8194f672)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff819506c6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff819516de)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/output_core.c (ffffffff81951add)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff819524f9)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81952957)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81953669)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (ffffffff8195ecde)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81963029)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In security/lsm_audit.c (ffffffff81421329)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81880ace)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/filter.c (ffffffff818b2207)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff818bfc31)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/nf_queue.c (ffffffff818e151d)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819165d2)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ping.c (ffffffff81939c72)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81951a38)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819639eb)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81964bd7)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81970865)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff8198284f)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81985356)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81987cbd)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff8198aa35)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8198c214)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819907fc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994b11)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff819969b1)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff819990c0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff8199b195)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6mr.c (ffffffff819a0b5b)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a1300)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff819a1ab5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1eb4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a2438)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff819a30c5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff819a4a54)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff819a6029)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7be1)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819a8ec0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9b94)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aabf2)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/output_core.c (ffffffff819ab06d)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff819aba72)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819abef5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad07d)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (ffffffff819b84c3)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:92
Inline: True
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In security/lsm_audit.c (ffffffff8143d9c9)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818a197e)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/filter.c (ffffffff818d6d71)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff818e8a51)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/nf_queue.c (ffffffff8190e0cb)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff8190ea4a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944d72)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ping.c (ffffffff819698ff)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81984cd8)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8199898d)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8199a03a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff819a6495)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819b8ee9)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bbad0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff819be5e4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff819c12f5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c2c9a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c6f49)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb405)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff819cd2ab)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff819cf8f8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff819d1af5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6mr.c (ffffffff819d776b)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7f40)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff819d86e5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8b09)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d90a5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff819d99b8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff819db574)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff819dc9d6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de72e)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819dfe77)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e06b4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e16e3)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff819e1b8a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff819e2611)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2ad5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3a2d)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (ffffffff819ef793)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:92
Inline: True
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In security/lsm_audit.c (ffffffff8146b589)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818ec36e)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/filter.c (ffffffff819245ea)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff81938263)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff8196fc3b)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff81970609)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8da1)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv4/ping.c (ffffffff819d056c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e8506)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff819eef18)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4ba8)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819f5e7c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a047f5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a05f8c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81a12bc1)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a27963)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a2a710)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a2c6dd)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a300bf)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a31abc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a361f7)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39e58)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c373)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a3e75d)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a408a5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6mr.c (ffffffff81a46808)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a46f45)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a47364)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a4791c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff81a485c4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a4a1e6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff81a4b416)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4d2a5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a4ea79)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f31e)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a504a1)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff81a5094b)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff81a512d4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a51815)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a528e0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81a5e9f4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:92
Inline: True
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In security/lsm_audit.c (ffffffff81485369)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8191e49e)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/filter.c (ffffffff819568fa)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff8196b123)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff819a6645)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff819a6ff9)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819dfa01)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81a070bc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1f516)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25de8)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b858)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2cafc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b3e5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a3cafc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81a497b1)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a5e3c3)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a61260)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a63b76)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a66c0f)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a6860c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a6cd17)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a709e8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81a72ff3)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a753cd)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a77525)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6mr.c (ffffffff81a7d3f8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a7daf5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7df14)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e4cc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff81a7f182)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a80dab)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff81a81fe6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83e75)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a85719)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a85fae)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a870c1)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff81a8756b)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87ef4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a88415)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a894c0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81a95624)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:92
Inline: True
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:93
Inline: True
```
```
In security/lsm_audit.c (ffffffff814db509)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819f1b1f)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
```
```
In net/core/filter.c (ffffffff81a2f56c)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff81a3ee72)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81a4cdfc)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f92e)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81a90359)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81accff4)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
```
```
In net/ipv4/ping.c (ffffffff81af76bc)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/ipv6.h:93
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11bf5)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
```
```
In net/xfrm/xfrm_state.c (ffffffff81b174f8)
Location: include/linux/ipv6.h:93
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e28d)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fb2f)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
```
```
In net/ipv6/ip6_output.c (ffffffff81b309b5)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b3219c)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81b401ed)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81b571b3)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b5a6b0)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b5c601)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b5f63f)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b618d5)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b66239)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a169)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d47a)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:seg6_update_csum
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81b6f609)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff81b717b5)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b77da3)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78c93)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b7907b)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b79493)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81b79e41)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81b7ba25)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff81b7d088)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7ec2b)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b806b0)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80fce)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:93
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b82374)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b82732)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81b82979)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff81b833b1)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b838e5)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84954)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81b90c34)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:93
Inline: True
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In security/lsm_audit.c (ffffffff814f8999)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819f17bf)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
```
```
In net/core/filter.c (ffffffff81a3187c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/netpoll.c (ffffffff81a41c12)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81a52ac3)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/bpf/test_run.c (ffffffff81a886b9)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81a9991e)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81a9a229)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad9001)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
```
```
In net/ipv4/ping.c (ffffffff81b0459c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06c7c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b2030a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
```
```
In net/xfrm/xfrm_state.c (ffffffff81b255b8)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2cb5c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e43f)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f5e5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b40dbc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81b4ebd5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81b65823)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b68db0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b6ae41)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b6dddf)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b70057)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b749b9)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78c4a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bf2a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:seg6_update_csum
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81b7e139)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff81b80455)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b86d23)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87c13)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b87ffb)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b8842a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81b88d91)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81b8aa65)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff81b8c138)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8dc45)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ff30)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b907ee)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91a68)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b91da5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81b91fdb)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92a61)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b92fa5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b942b4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81ba08ef)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81bc136b)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:93
Inline: True
```
```
In security/lsm_audit.c (ffffffff814ff709)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819d6a4f)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
```
```
In net/core/filter.c (ffffffff81a186dc)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/netpoll.c (ffffffff81a266f7)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81a382c3)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/bpf/test_run.c (ffffffff81a71919)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81a84c2e)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81a85523)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp.c (ffffffff81aa580e)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac45bb)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ping.c (ffffffff81aef5ac)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af23b2)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0e1ea)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
```
```
In net/xfrm/xfrm_state.c (ffffffff81b130d8)
Location: include/linux/ipv6.h:93
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a797)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1beaf)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d47f)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b2ece0)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81b3ca05)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81b53ad3)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b56e48)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b5914c)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b5c162)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b5e319)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81b634dd)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6779c)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81b6aa0e)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81b6cd19)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f055)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b759e1)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b768d0)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76d2b)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b7715a)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81b77bb1)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81b798c9)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff81b7afb8)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7cb17)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f061)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fa1c)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:93
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80cb9)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b80ff9)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81b8126b)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81bb9)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b820f5)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b833c0)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81b8f9bf)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:93
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81bb1d1b)
Location: include/linux/ipv6.h:93
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:96
Inline: True
```
```
In security/lsm_audit.c (ffffffff8155a779)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81a8709f)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
```
```
In net/core/filter.c (ffffffff81ac9bcc)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/netpoll.c (ffffffff81adb472)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81ae1a96)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
```
```
In net/core/lwt_bpf.c (ffffffff81aee12c)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/bpf/test_run.c (ffffffff81b2b030)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f23a)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81b3fc13)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp.c (ffffffff81b61b5e)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82dab)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ping.c (ffffffff81bb0b38)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb28c2)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd161a)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd6fd8)
Location: include/linux/ipv6.h:96
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdedb7)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81be065f)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3650)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81bf5010)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81c03356)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81c1b013)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81c1d068)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81c20725)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81c238c9)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81c257c9)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81c2af9d)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f3cc)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81c3286e)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81c34c26)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff81c37115)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff81c38f3d)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81c40405)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c41354)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c417db)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81c41bfa)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81c426d1)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81c44573)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff81c45c78)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47c86)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a8b1)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b2bc)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4c118)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:96
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4ccd9)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff81c4d019)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81c4d290)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dc09)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e1a5)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f490)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81c5c15f)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:96
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81c7fda8)
Location: include/linux/ipv6.h:96
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:98
Inline: True
```
```
In security/lsm_audit.c (ffffffff815f54f5)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81bfc850)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
```
```
In net/core/filter.c (ffffffff81c473d8)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/gro.c (ffffffff81c54bd1)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/netpoll.c (ffffffff81c5c926)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81c6580c)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
```
```
In net/core/lwt_bpf.c (ffffffff81c70f51)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/bpf/test_run.c (ffffffff81cb5255)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb991)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81ccc433)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp.c (ffffffff81cf05bd)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d1337e)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ping.c (ffffffff81d440b0)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d46099)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6772a)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d968)
Location: include/linux/ipv6.h:98
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81d76610)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81d776aa)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c225)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81d8de5c)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81d9d2fa)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81db7629)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81dbbbd0)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81dbd4bd)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81dc07fb)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81dc2f60)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81dc824d)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd634)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81dd0063)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81dd25c9)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff81dd4cb5)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff81dd6eb1)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81ddea38)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddfad7)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddfdbb)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81de04bb)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81de117a)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81de3574)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff81de4e18)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de70f1)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81dea1cb)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deac0b)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec33d)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:98
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded150)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff81ded4ce)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81ded7ac)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee2c9)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deea65)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defebb)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81dfdee7)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:98
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81e257a4)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:98
Inline: True
```
```
In security/lsm_audit.c (ffffffff816a5ff8)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81dab770)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
```
```
In net/core/filter.c (ffffffff81dfb938)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/gro.c (ffffffff81e0a35c)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/netpoll.c (ffffffff81e13016)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81e1c4c9)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
```
```
In net/core/lwt_bpf.c (ffffffff81e28fd1)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/bpf/test_run.c (ffffffff81e737b3)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b7e1)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81e8c333)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp.c (ffffffff81eb38f1)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed92ee)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ping.c (ffffffff81f0d57f)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f479)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3278a)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38f58)
Location: include/linux/ipv6.h:98
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42d72)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_beet_make_header
  - net/xfrm/xfrm_input.c:xfrm6_extract_header
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43f62)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm6_beet_make_header
  - net/xfrm/xfrm_output.c:xfrm6_extract_header
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a1e5)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bfcc)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81f6c22a)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81f87319)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81f8bcf0)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81f8d9fd)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81f90f86)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81f939b0)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81f98fdd)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e747)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81fa13f3)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81fa3a49)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6375)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff81fa8871)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81fb0c2c)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1dc7)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb20db)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81fb284b)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81fb35da)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81fb5bf4)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff81fb75a8)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9f81)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81fbda8b)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe7cb)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbff8d)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:98
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc0f60)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff81fc12ee)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81fc15dc)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc284e)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2aa5)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3fdb)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81fd2aa7)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:98
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81ffd3f4)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:98
Inline: True
```
```
In security/lsm_audit.c (ffffffff816de9d8)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81e1b270)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
```
```
In net/core/filter.c (ffffffff81e6c838)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/netpoll.c (ffffffff81e86951)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81e90889)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
```
```
In net/core/lwt_bpf.c (ffffffff81e9e617)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/bpf/test_run.c (ffffffff81ecf6d3)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81ee982b)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81eea671)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp.c (ffffffff81f1209e)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f383d6)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ping.c (ffffffff81f6d1e1)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f169)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9391c)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
```
```
In net/xfrm/xfrm_state.c (ffffffff81f987e1)
Location: include/linux/ipv6.h:98
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa2551)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_beet_make_header
  - net/xfrm/xfrm_input.c:xfrm6_extract_header
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa45d5)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm6_beet_make_header
  - net/xfrm/xfrm_output.c:xfrm6_extract_header
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9e98)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81fbbd7c)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81fcc365)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81fe765a)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81fec490)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81fee1d9)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81ff1876)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81ff4309)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81ff99ad)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81fff203)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff82001c93)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
```
```
In net/ipv6/datagram.c (ffffffff82004181)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff82006bf5)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff82009201)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff820112e2)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff820124d5)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff820127e8)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff82012f60)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff82013cc7)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff82016305)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff82017cf8)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a6b4)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201eaab)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f66b)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020f0b)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:98
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff82021ef0)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff8202226e)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff8202255c)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff820237cc)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023a35)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024ffb)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/netlabel/netlabel_kapi.c (ffffffff8204e6fa)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:98
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff820796c4)
Location: include/linux/ipv6.h:98
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:100
Inline: True
```
```
In security/lsm_audit.c (ffffffff8171b5a8)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81ed8830)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
```
```
In net/core/filter.c (ffffffff81f2c118)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/netpoll.c (ffffffff81f4895e)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81f52c59)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
```
```
In net/core/lwt_bpf.c (ffffffff81f60d90)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/bpf/test_run.c (ffffffff81f93023)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81fad54c)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81fae421)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp.c (ffffffff81fcf5c6)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81fdbd5a)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_rcv_spurious_retrans
  - net/ipv4/tcp_input.c:tcp_rcv_spurious_retrans
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/ipv6.h:100
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe496)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/ping.c (ffffffff8203392d)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035899)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
```
```
In net/ipv4/tcp_ao.c (ffffffff82058a34)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_ao_prepare_reset
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff82065b51)
Location: include/linux/ipv6.h:100
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f892)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_beet_make_header
  - net/xfrm/xfrm_input.c:xfrm6_extract_header
```
```
In net/xfrm/xfrm_output.c (ffffffff82071913)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm6_beet_make_header
  - net/xfrm/xfrm_output.c:xfrm6_extract_header
```
```
In net/ipv6/ip6_output.c (ffffffff8208734e)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff820891ac)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff82099b48)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff820b54ba)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff820ba0a0)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff820bbdb0)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff820bf475)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff820c125a)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff820c761d)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cdf13)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:__inet6_lookup_skb
```
```
In net/ipv6/exthdrs.c (ffffffff820d0b0a)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
```
```
In net/ipv6/datagram.c (ffffffff820d2f41)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff820d5a55)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff820d81a1)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff820e0272)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e0eee)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e1966)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff820e20c0)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff820e2e24)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff820e542e)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff820e6cc8)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e9671)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820edbdb)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:input_action_end_x_core
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee79b)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820f0038)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:100
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f1010)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff820f138e)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff820f167c)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff820f20d0)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2b95)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f42db)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/ipv6/tcp_ao.c (ffffffff820f4875)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/ipv6/tcp_ao.c:tcp_v6_ao_calc_key_skb
```
```
In net/netlabel/netlabel_kapi.c (ffffffff82120d7a)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:100
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff8214eb14)
Location: include/linux/ipv6.h:100
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In security/lsm_audit.c (ffff80001057786c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffff800010bb8c0c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/filter.c (ffff800010bf81e8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffff800010c115c4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netfilter/nf_queue.c (ffff800010c55ecc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffff800010c56a68)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93324)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv4/ping.c (ffff800010cbfff4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdb4ac)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffff800010ce33c4)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffff800010cea2e0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010ceb770)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffff800010cfc4f8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffff800010cfde70)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffff800010d11edc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffff800010d233fc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d244cc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffff800010d29c2c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffff800010d2cb6c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d2ff6c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffff800010d3586c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38ec8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffff800010d3bac0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffff800010d3da78)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffff800010d40bb0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6mr.c (ffff800010d480a8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffff800010d48d58)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffff800010d492e0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffff800010d4993c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffff800010d4a420)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffff800010d4c628)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffff800010d4d66c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4fbc0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffff800010d517c8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffff800010d52884)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffff800010d53820)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffff800010d53e60)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffff800010d54a8c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d54fb8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffff800010d562e0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/netlabel/netlabel_kapi.c (ffff800010d642e8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:92
Inline: True
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In security/lsm_audit.c (c072a694)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (c0cd56c8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/filter.c (c0d11c80)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (c0d29640)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netfilter/nf_queue.c (c0d658dc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (c0d66218)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_fastopen.c (c0da1e04)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv4/ping.c (c0dcc4e8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (c0de5e18)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (c0dec9ac)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (c0df2754)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_output.c (c0df3650)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c0e038f4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c0e05918)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (c0e12cc8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (c0e27a44)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c0e2b320)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (c0e2d9c0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c0e30a44)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e338a8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c0e37a90)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c0e3ba68)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (c0e3e560)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (c0e41038)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (c0e43588)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6mr.c (c0e49ab8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (c0e4a200)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (c0e4a6a8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (c0e4acb4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (c0e4ba2c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (c0e4d8d8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (c0e4ed48)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (c0e50918)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c0e5236c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (c0e52d5c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (c0e54100)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (c0e54604)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (c0e55094)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (c0e5556c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (c0e568dc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/netlabel/netlabel_kapi.c (c0e62f04)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:92
Inline: True
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In security/lsm_audit.c (c0000000006e0ec0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (c000000000c90fb8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/filter.c (c000000000cdec40)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (c000000000cfe2c4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netfilter/nf_queue.c (c000000000d56750)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (c000000000d5764c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_fastopen.c (c000000000da38b0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv4/ping.c (c000000000ddb374)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (c000000000e004dc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (c000000000e06acc)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (c000000000e0dddc)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_output.c (c000000000e0f554)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c000000000e24020)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c000000000e2611c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (c000000000e37f10)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (c000000000e53394)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c000000000e56d50)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (c000000000e5aa40)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c000000000e5e648)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c000000000e61328)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c000000000e6792c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c39c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (c000000000e6f3b8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (c000000000e722e0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (c000000000e752a8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6mr.c (c000000000e7d594)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (c000000000e7e108)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e804)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (c000000000e7f014)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (c000000000e80490)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (c000000000e82ce0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (c000000000e8460c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e87440)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c000000000e89a20)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (c000000000e8af4c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (c000000000e8c028)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (c000000000e8c7a8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (c000000000e8d610)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8dcb4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f498)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/netlabel/netlabel_kapi.c (c000000000e9fbe8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:92
Inline: True
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In security/lsm_audit.c (ffffffe0003c9d78)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffe0007482d6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/filter.c (ffffffe000779eb0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffe00078d786)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffe0007c027a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffe0007c0a74)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2aaa)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv4/ping.c (ffffffe000816a7c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082cde0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffe000831bfe)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffe000837f14)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe0008390e8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffe000846da8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffe0008482dc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffe000853ece)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffe000864d6a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffe000867ffc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffe00086a450)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffe00086cdf6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffe00086f6f4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffe000872d20)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008762a6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffe000878552)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffe00087a14a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffe00087c3fa)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6mr.c (ffffffe000881bcc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffe0008822b4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffe0008827be)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882d2c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffe00088392a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffe00088535c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffe00088687c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe0008882c6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffe0008899ba)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a882)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b500)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffe00088b9a2)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c412)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c840)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088db58)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/netlabel/netlabel_kapi.c (ffffffe00089837c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:92
Inline: True
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In security/lsm_audit.c (ffffffff8147d949)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818be49e)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/filter.c (ffffffff818f68ca)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff8190b0f3)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff819464b5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff81946e69)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f871)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv4/ping.c (ffffffff819a6e5c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff819beba6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff819c5478)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff819caee8)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc18c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff819daa75)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff819dc18c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff819e8e41)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819fda53)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a008f0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a03206)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a0629f)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a07c9c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a0c3a7)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10078)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81a12683)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a14a5d)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a16bb5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6mr.c (ffffffff81a1ca88)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a1d185)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d5a4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1db5c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff81a1e812)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a2043b)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff81a21676)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a23505)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a24da9)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a2563e)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a26751)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff81a26bfb)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff81a27584)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27aa5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28b50)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81a349b4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:92
Inline: True
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In security/lsm_audit.c (ffffffff8146e369)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In drivers/net/vxlan.c (ffffffff81773efb)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/skbuff.c (ffffffff818783de)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/filter.c (ffffffff818b06fa)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff818c4e78)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff818fffa5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff81900959)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939331)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv4/ping.c (ffffffff8196091c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel.c (ffffffff8196782f)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv4/udp_tunnel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197b996)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff81982268)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81987cd8)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81988f7c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81997835)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81998f4c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff819a5c01)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819ba813)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bd6b0)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff819bffc6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff819c305f)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c4a5c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c9167)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cce38)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff819cf443)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff819d181d)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff819d3975)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6mr.c (ffffffff819d9848)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffff819d9f45)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da364)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819da91c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff819db5d2)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff819dd1fb)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff819de436)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819e02c5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819e1b69)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e23fe)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e3511)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff819e39bb)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4344)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e4865)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/ip6_udp_tunnel.c (ffffffff819e5abf)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_udp_tunnel.c:udp_tunnel6_xmit_skb
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5d40)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/netlabel/netlabel_kapi.c (ffffffff819f15d4)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:92
Inline: True
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In security/lsm_audit.c (ffffffff814799e9)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8190f49e)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/filter.c (ffffffff819478fa)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff8195c123)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff81997645)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff81997ff9)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a4a39)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netfilter/nf_conntrack_proto_icmpv6.c (ffffffff819a89a2)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmpv6.c:nf_conntrack_icmpv6_error
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819ea041)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81a116fc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a29626)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2fef8)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35968)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36c0c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a454f5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a46c0c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81a538c1)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a684d3)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a6b370)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a6dc86)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a70d1f)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a7271c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a76e27)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7aaf8)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d103)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a7f4dd)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a81635)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6mr.c (ffffffff81a87508)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a87c05)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a88024)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a885dc)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff81a89292)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a8aebb)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff81a8c0f6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8df85)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f829)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a900be)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a910de)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a92301)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff81a927ab)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff81a93134)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a93655)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a94700)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81aa0864)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:92
Inline: True
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
In security/selinux/netlabel.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In security/lsm_audit.c (ffffffff81491499)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819305ce)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/filter.c (ffffffff8196920a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/netpoll.c (ffffffff8197e503)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff819ba325)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff819bacd9)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3e71)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81a1c06c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a34bb6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3b878)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81a412d3)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a4259c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a511c5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a5297e)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81a5f8b1)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a74ac3)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a77980)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a7a2a6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a7d32f)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a7eda6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a83447)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87338)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_ts_off
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81a89953)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a8bd9d)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a8df35)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
```
In net/ipv6/ip6mr.c (ffffffff81a940de)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a94835)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94c44)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a9522c)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff81a95ef2)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a97b19)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff81a98ff6)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9acc9)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c5a9)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d31a)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e3b1)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff81a9e88f)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f2ce)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f7a5)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0860)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81aacae7)
Location: include/linux/ipv6.h:92
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ipv6.h:92
Inline: True
```
</details>
</li>
</ul>

## Differences
