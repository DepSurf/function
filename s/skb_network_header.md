# Function: <code>skb_network_header</code>

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
In kernel/bpf/core.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In security/lsm_audit.c (ffffffff813661c6)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff817095da)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/core/dev.c (ffffffff8171c993)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/neighbour.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/core/tso.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/core/netpoll.c (ffffffff81739490)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/ipv4/route.c (ffffffff81753384)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_get_source
```
```
In net/ipv4/ip_input.c (ffffffff81758739)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817596d3)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff8175a89c)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff8175b3a7)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_build
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_forward_options
```
```
In net/ipv4/ip_output.c (ffffffff8175c712)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761a77)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177a9f4)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782ccb)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81783175)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff8178512a)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8178a04c)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/udp_offload.c (ffffffff8178b35e)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffff8178caa0)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8178e1d1)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff817949e8)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8179626e)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/fib_frontend.c (ffffffff8179aaab)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff817a2489)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a482c)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff817a73d4)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_get_route
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff817ac188)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817ae095)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff817af6c1)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff817afd45)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff817afdbb)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff817b020a)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_state.c (ffffffff817b7fbc)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c4d2a)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff817c85af)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff817d6fba)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff817dea83)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff817e4990)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff817e6c35)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff817e772c)
Location: include/linux/skbuff.h:2013
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
Location: include/linux/skbuff.h:2013
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
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817eee4c)
Location: include/linux/skbuff.h:2013
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
In net/ipv6/exthdrs.c (ffffffff817f2b65)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (ffffffff817f4bd9)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/ip6mr.c (ffffffff817f8d28)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_get_route
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fc2c3)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff817fca75)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd1ff)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
```
```
In net/ipv6/netfilter.c (ffffffff817fdbc1)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/ipv6/exthdrs_core.c (ffffffff817ffaf6)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/ip6_checksum.c (ffffffff818002d8)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff818004c6)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:__ip6_local_out
```
```
In net/ipv6/ip6_offload.c (ffffffff81800f0b)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff8180128e)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/udp_offload.c (ffffffff818015f3)
Location: include/linux/skbuff.h:2013
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/mcast_snoop.c (ffffffff818025da)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/linux/skbuff.h:2013
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/skbuff.h:2013
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
In kernel/bpf/core.c (ffffffff811805c6)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In security/selinux/hooks.c (ffffffff8137e00d)
Location: include/linux/skbuff.h:2143
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813982f7)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff8139c352)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81771e7a)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffffffff81779a33)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81781c70)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:__skb_csum_offload_chk
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff8178f366)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/tso.c (ffffffff8179fd31)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff817a5744)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff817a8204)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff817c3554)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff817c528d)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff817c5c24)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff817c6bb3)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff817c76ab)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff817cb951)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cdf97)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff817dc573)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb870)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817f0308)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0705)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff817f1bea)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff817f7f50)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff817f8482)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff817fa0a0)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff817fc88e)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/af_inet.c (ffffffff81802377)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8180577a)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff818086db)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81810634)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818124dc)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818187d4)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81818f89)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff818197d9)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181c07b)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8181c924)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff8181cc75)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181cd35)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8181d2f5)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_state.c (ffffffff818251cc)
Location: include/linux/skbuff.h:2143
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81828926)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/af_inet6.c (ffffffff8182fa13)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81834f11)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
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
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81841514)
Location: include/linux/skbuff.h:2143
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
Location: include/linux/skbuff.h:2143
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
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff818545fa)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff818570b1)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81859673)
Location: include/linux/skbuff.h:2143
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
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818603e0)
Location: include/linux/skbuff.h:2143
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
In net/ipv6/exthdrs.c (ffffffff81861b4d)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff818643ca)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff8186695a)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8186b41f)
Location: include/linux/skbuff.h:2143
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186bbc3)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff8186c395)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff8186c449)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186cc1b)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff8186d81c)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff8186ecc9)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff81870069)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/exthdrs_core.c (ffffffff818713bd)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81871946)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff81871d3f)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81872845)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872ace)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818738dd)
Location: include/linux/skbuff.h:2143
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818785cc)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff8187de8e)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818822f7)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff8188dcda)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff8188e1ac)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
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
In kernel/bpf/core.c (ffffffff8118c436)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In kernel/bpf/cgroup.c (ffffffff81197643)
Location: include/linux/skbuff.h:2160
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81394a9d)
Location: include/linux/skbuff.h:2160
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813aeed7)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff813b2f02)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8179ef95)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffffffff817a6a68)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff817af580)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff817bcc16)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (0)
Location: include/linux/skbuff.h:2160
Inline: True
```
```
In net/core/tso.c (ffffffff817ce701)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff817d41b4)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff817d6d52)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff817f2b46)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff817f4d9d)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5724)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff817f66b3)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff817f719b)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff817fb5b3)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdcf7)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff8180c640)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c1e0)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81820d43)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81821475)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff818229da)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81828df0)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81829332)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff8182af70)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff8182d7f1)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/af_inet.c (ffffffff81833309)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81836bca)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff8183978b)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81841b34)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818439e0)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8184a034)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff8184a7e9)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff8184b099)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184d93b)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8184e1cb)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff8184e545)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e605)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8184eba5)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_state.c (ffffffff81856b2c)
Location: include/linux/skbuff.h:2160
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a306)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/af_inet6.c (ffffffff81861493)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81866a47)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
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
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81873374)
Location: include/linux/skbuff.h:2160
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
Location: include/linux/skbuff.h:2160
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
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81886323)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81888eb1)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8188b4a3)
Location: include/linux/skbuff.h:2160
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
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892370)
Location: include/linux/skbuff.h:2160
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
In net/ipv6/exthdrs.c (ffffffff81893abd)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81896ab8)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff8189905a)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8189e27f)
Location: include/linux/skbuff.h:2160
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189ea20)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff8189f1a5)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff8189f259)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189fa0b)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff818a061c)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff818a1c19)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/calipso.c (ffffffff818a2fd9)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_skbuff_optptr
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a46d6)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a4ee0)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffff818a590c)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5ea6)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff818a62ad)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6e4c)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a70ee)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a7f5d)
Location: include/linux/skbuff.h:2160
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818ace22)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff818b273e)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b6ba7)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff818c1e8a)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff818c244c)
Location: include/linux/skbuff.h:2160
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
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
In kernel/bpf/core.c (ffffffff81190d70)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
```
```
In kernel/bpf/cgroup.c (ffffffff8119f2d5)
Location: include/linux/skbuff.h:2199
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813aab47)
Location: include/linux/skbuff.h:2199
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813c547c)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff813c98d4)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff817bc6f1)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffffffff817c4dcf)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff817cde90)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff817db2dd)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff817eadb2)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/tso.c (ffffffff817edbb1)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff817f34fd)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff817f6dc2)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff818134ea)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff81815231)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81815bc0)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81816acd)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81817576)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff8181b985)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e25c)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff8182c580)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cc40)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840f95)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81842155)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff8184365c)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8184a0d0)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8184aaf4)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff8184c1c4)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff8184ed48)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81854668)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81856d79)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff8185acfb)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff818632ec)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8186523f)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8186da89)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff8186e191)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff8186eb19)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8187139b)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81871b3b)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff81871f75)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81872035)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8187274c)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_state.c (ffffffff8187a4a8)
Location: include/linux/skbuff.h:2199
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e188)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/af_inet6.c (ffffffff81885bd3)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff8188b174)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
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
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81897d43)
Location: include/linux/skbuff.h:2199
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
Location: include/linux/skbuff.h:2199
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
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff818aca7a)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff818af597)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff818b1229)
Location: include/linux/skbuff.h:2199
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
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b89cf)
Location: include/linux/skbuff.h:2199
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
In net/ipv6/exthdrs.c (ffffffff818ba01d)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff818bd031)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff818bf279)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff818c483c)
Location: include/linux/skbuff.h:2199
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c4fa2)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff818c5715)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff818c57b9)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c5faa)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff818c6c61)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff818c81e3)
Location: include/linux/skbuff.h:2199
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
Location: include/linux/skbuff.h:2199
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
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb926)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffff818cc38c)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc927)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff818cccfd)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd712)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdb5e)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce7b9)
Location: include/linux/skbuff.h:2199
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d55a5)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff818d90ee)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dd487)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff818e87fa)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff818e8ddc)
Location: include/linux/skbuff.h:2199
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
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
In kernel/bpf/core.c (ffffffff8119d068)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff811b24ae)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff813d0ba7)
Location: include/linux/skbuff.h:2286
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813eb54c)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff813efd64)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81836dc1)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffffffff8183e8bf)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff8184ab64)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81855a9d)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff8186786f)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/tso.c (ffffffff81869df1)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff8186e8ed)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff818733a5)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff81892b3a)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff81894401)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81894d97)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81895c8d)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81896736)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff8189a8be)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189d16c)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff818ab453)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc5ec)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0997)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1a35)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff818c303c)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff818c9c7d)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff818ca794)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff818cbe74)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff818ceace)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff818d4508)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff818d6c29)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff818dac2b)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff818e3428)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e539f)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818ee3c9)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff818eeb21)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff818ef4d9)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f1d8b)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff818f24fb)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff818f2935)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2a15)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f314c)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_state.c (ffffffff818faf18)
Location: include/linux/skbuff.h:2286
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff224)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/af_inet6.c (ffffffff81906d83)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff8190c394)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
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
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff819190c3)
Location: include/linux/skbuff.h:2286
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
Location: include/linux/skbuff.h:2286
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
In net/ipv6/udp.c (ffffffff8192cc6c)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff8192f2d7)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff819322ad)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81933879)
Location: include/linux/skbuff.h:2286
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
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b881)
Location: include/linux/skbuff.h:2286
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
In net/ipv6/exthdrs.c (ffffffff8193cffd)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81940151)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff819423c9)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81947adc)
Location: include/linux/skbuff.h:2286
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81948272)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff819489f5)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948a99)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff8194934e)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff8194a121)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff8194b793)
Location: include/linux/skbuff.h:2286
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
Location: include/linux/skbuff.h:2286
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
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8194fb32)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:lookup_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff819506c6)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffff8195113c)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819516de)
Location: include/linux/skbuff.h:2286
Inline: True
```
```
In net/ipv6/output_core.c (ffffffff81951add)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81952504)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff8195295e)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81953669)
Location: include/linux/skbuff.h:2286
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8195a055)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff8195ecde)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81963077)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff8196dc7a)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff8196e31c)
Location: include/linux/skbuff.h:2286
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
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
In kernel/bpf/core.c (ffffffff811b1798)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff811d1af5)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff813fde1e)
Location: include/linux/skbuff.h:2297
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff81417d48)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff8141ce84)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff81421329)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81880eff)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffffffff8188927b)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81894f44)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff818a15c0)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff818b2207)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/tso.c (ffffffff818b9ac1)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff818bfa79)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff818c4b1f)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff818e151d)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff818e480c)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff818e8693)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff818e8e8f)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff818e9f4d)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff818ea9c5)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff818eedab)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f1502)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff819008ae)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81912243)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819165d2)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81917702)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81918b16)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8191fd23)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819202cd)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81922354)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81924e60)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8192abeb)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8192dd25)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81931bf3)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81939d56)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193bc6d)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81943fb5)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff8194543c)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff81945e45)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81948687)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81948dde)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff81949275)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81949355)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81949a7d)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_state.c (ffffffff81951a38)
Location: include/linux/skbuff.h:2297
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81955be6)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/af_inet6.c (ffffffff8195dd73)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff8196381b)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv6/ip6_input.c (ffffffff81964bd7)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/route.c (ffffffff81970865)
Location: include/linux/skbuff.h:2297
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
Location: include/linux/skbuff.h:2297
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
In net/ipv6/udp.c (ffffffff81985356)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81987cbd)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff8198abb3)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8198c214)
Location: include/linux/skbuff.h:2297
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
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994b11)
Location: include/linux/skbuff.h:2297
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
In net/ipv6/exthdrs.c (ffffffff81996035)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff819990c0)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff8199b1ab)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff819a0b5b)
Location: include/linux/skbuff.h:2297
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a1300)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff819a1ab5)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1b55)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a2438)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff819a30c5)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff819a4a54)
Location: include/linux/skbuff.h:2297
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
Location: include/linux/skbuff.h:2297
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
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819a8ec0)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9b94)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffff819aa6ee)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aabf2)
Location: include/linux/skbuff.h:2297
Inline: True
```
```
In net/ipv6/output_core.c (ffffffff819ab06d)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff819aba7d)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819abf0e)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad07d)
Location: include/linux/skbuff.h:2297
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819af067)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff819b84c3)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bc887)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff819c77ac)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff819c7d55)
Location: include/linux/skbuff.h:2297
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
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
In kernel/bpf/core.c (ffffffff811bfe28)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff811e1815)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff81419cce)
Location: include/linux/skbuff.h:2375
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff81434274)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814387bb)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff8143d9c9)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818a1d96)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffffffff818a9ac3)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818b5a24)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff818c38fd)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff818d5aa9)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/tso.c (ffffffff818e0881)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff818e8899)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff818edb8f)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff8190e0cb)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff8190ea4a)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81911736)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff8191591b)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81916073)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff8191736f)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81917735)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff8191c59a)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191f05f)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff8192ed74)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940a20)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944d72)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81945e3f)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff819472e3)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8194e98d)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8194efe5)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81951184)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81953c72)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8195a375)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8195d5f5)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81961453)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff819699e7)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bac6)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81974105)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff819757e2)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff81975e53)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197a364)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8197aaae)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff8197af25)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b005)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b73d)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_state.c (ffffffff81984cd8)
Location: include/linux/skbuff.h:2375
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a6c8)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/af_inet6.c (ffffffff819928b3)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff819987db)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/ipv6/ip6_input.c (ffffffff8199a03a)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819a6495)
Location: include/linux/skbuff.h:2375
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
Location: include/linux/skbuff.h:2375
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
In net/ipv6/udp.c (ffffffff819bbad0)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff819be5e4)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff819c1481)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c2c9a)
Location: include/linux/skbuff.h:2375
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
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb405)
Location: include/linux/skbuff.h:2375
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
In net/ipv6/exthdrs.c (ffffffff819cc945)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff819cf8f8)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff819d1af5)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff819d776b)
Location: include/linux/skbuff.h:2375
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7f40)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
```
In net/ipv6/xfrm6_state.c (ffffffff819d86e5)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8785)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d90a5)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff819d99b8)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff819db574)
Location: include/linux/skbuff.h:2375
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
Location: include/linux/skbuff.h:2375
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
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819dfe77)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e06b4)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffff819e11ee)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e16e3)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff819e1b8a)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff819e261d)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2aee)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3a2d)
Location: include/linux/skbuff.h:2375
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e5a31)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff819ef793)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f3ad7)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff819ff1cb)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff819ff9b5)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a00ee7)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
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
In kernel/bpf/core.c (ffffffff811d0658)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff811f88f5)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff81447721)
Location: include/linux/skbuff.h:2463
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff81461d15)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff8146640b)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff8146b589)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818ecb76)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffffffff818f5a2e)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818ff38c)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff8190faad)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff8192324c)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/tso.c (ffffffff8192ef11)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff819380ab)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff8193e4c5)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff819436a1)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff8196fc3b)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff819707ba)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81973c96)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff81977e9c)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81978c58)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819792aa)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81979e35)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff8197e8c0)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff819819ac)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff8198df17)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4fa9)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8d70)
Location: include/linux/skbuff.h:2463
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa475)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff819ab963)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819b3174)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819b37d5)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff819b5a44)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff819b856c)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff819beef5)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff819c2265)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff819c5c34)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf0a7)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff819d067c)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d27ea)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819ddbd5)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff819df301)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff819df9e2)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e3ea4)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_state.c (ffffffff819e4415)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e4505)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4c7d)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e8506)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff819eef18)
Location: include/linux/skbuff.h:2463
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff819f52c5)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f5e7c)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (ffffffff819fe1d3)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81a04633)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv6/ip6_input.c (ffffffff81a05f8c)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a12bc1)
Location: include/linux/skbuff.h:2463
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
Location: include/linux/skbuff.h:2463
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
In net/ipv6/udp.c (ffffffff81a2a710)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a2c6dd)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a3025c)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a31abc)
Location: include/linux/skbuff.h:2463
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
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39e58)
Location: include/linux/skbuff.h:2463
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
In net/ipv6/exthdrs.c (ffffffff81a3b425)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a3e75d)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a408a5)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a46808)
Location: include/linux/skbuff.h:2463
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a46f45)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a46fe5)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a4791c)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff81a485c4)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a4a1e6)
Location: include/linux/skbuff.h:2463
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
Location: include/linux/skbuff.h:2463
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
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a4ea79)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f31e)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a4ffbe)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a504a1)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff81a5094b)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81a512e0)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a5183c)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a528e0)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffff81a55463)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81a5e9f4)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a62f07)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a6e4cb)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff81a6ec85)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a700b4)
Location: include/linux/skbuff.h:2463
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
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
In kernel/bpf/core.c (ffffffff811dcbe8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff81205925)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff814612b1)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff8147bac5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814801eb)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff81485369)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8191ec96)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffffffff8192792b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819316f3)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff8194211d)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff8195547c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/tso.c (ffffffff81961181)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff8196af6b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81971355)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff8197868b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff819a6645)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff819a71aa)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819aa6b6)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff819ae80c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff819af5c8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819afc1a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff819b0795)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff819b5260)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b81ec)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff819c4ae7)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbca9)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df9d0)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1145)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff819e2633)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819e9ef4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819ea505)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff819ec764)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff819ef26c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff819f5b35)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff819f8e05)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff819fc7e4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05c47)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff81a071cc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a091ea)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a14d1d)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81a16397)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff81a16a12)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a1ae94)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_state.c (ffffffff81a1b425)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b515)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1bc9d)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1f516)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25de8)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2bf75)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2cafc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (ffffffff81a34dc3)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b223)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv6/ip6_input.c (ffffffff81a3cafc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a497b1)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
In net/ipv6/udp.c (ffffffff81a61260)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a63b76)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a66dac)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a6860c)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a709e8)
Location: include/linux/skbuff.h:2477
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
In net/ipv6/exthdrs.c (ffffffff81a720a5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a753cd)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a77525)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a7d3f8)
Location: include/linux/skbuff.h:2477
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a7daf5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7db95)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e4cc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff81a7f182)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a80dab)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a85719)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a85fae)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a86c0e)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a870c1)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff81a8756b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87f00)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a8843c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a894c0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffff81a8c533)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81a95624)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a99ae7)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81aa4e9b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff81aa5655)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff81aa68e4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
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
In kernel/bpf/core.c (ffffffff811f9608)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff8122cb35)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff814b42bb)
Location: include/linux/skbuff.h:2500
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff814d1075)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814d6853)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff814db509)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819f1576)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff819fbbd3)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a06e73)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81a1207d)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a2829e)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a34694)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff81a3ecd4)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81a452ad)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81a4d63a)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f92e)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81a9050a)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a949f6)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff81a97e89)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81a99448)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81a99aea)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81a9a625)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff81a9f4bb)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2b0c)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff81aaffaf)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac85d6)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81accf95)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ace725)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81ad046a)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81ad7ad2)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err_encap
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad81d5)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
```
```
In net/ipv4/arp.c (ffffffff81ada6f4)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81add1ae)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81ae4025)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81ae6ca9)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeb574)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5357)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff81af77cc)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af87b5)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b01f8a)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81b073a9)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff81b07a52)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0befb)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c5d5)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b0cb5d)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81b0cdeb)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11d79)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81b174f8)
Location: include/linux/skbuff.h:2500
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e426)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fb2f)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/ipv6/af_inet6.c (ffffffff81b29c33)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81b307d9)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
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
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81b401ed)
Location: include/linux/skbuff.h:2500
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
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err_encap
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b5c601)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b5f829)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b618d5)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b66239)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a169)
Location: include/linux/skbuff.h:2500
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
In net/ipv6/exthdrs.c (ffffffff81b6bc45)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:seg6_update_csum
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b6f609)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81b717b5)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b77da3)
Location: include/linux/skbuff.h:2500
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78725)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b7907b)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b79493)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81b79e41)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81b7ba25)
Location: include/linux/skbuff.h:2500
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
Location: include/linux/skbuff.h:2500
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
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b806b0)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80fce)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b81ebe)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b82374)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b826dd)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81b82979)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81b833b1)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b838e5)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84954)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
```
In net/packet/af_packet.c (ffffffff81b878f8)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81b90c34)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b95327)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81ba096b)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff81ba1125)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba2764)
Location: include/linux/skbuff.h:2500
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
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
In kernel/bpf/core.c (ffffffff811f8648)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff81234fb5)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff814d1a1b)
Location: include/linux/skbuff.h:2521
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff814ee585)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814f3602)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff814f8999)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819f15da)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff819fb2e5)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a083f3)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81a1241d)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a28aae)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a369ad)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff81a41a74)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81a494c2)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff81a53301)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/sched/sch_frag.c (ffffffff81a6f634)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/bpf/test_run.c (ffffffff81a886b9)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81a9991e)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81a9a3da)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a9e9f6)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff81aa1de9)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa33b8)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3a3a)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81aa4585)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff81aa93fb)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aace1c)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff81abafda)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4576)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8f99)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ada745)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81adc47a)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81ae4122)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err_encap
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4875)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff81ae7194)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81ae9efe)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81af0f55)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81af3b79)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81af8474)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff81b020b7)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff81b046ac)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05605)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b102fb)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81b15777)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff81b15e30)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b1a28b)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1a8f5)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b1ae9d)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81b1b12b)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b20479)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81b255b8)
Location: include/linux/skbuff.h:2521
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2ccf6)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e43f)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/ipv6/af_inet6.c (ffffffff81b38573)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f409)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
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
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81b4ebd5)
Location: include/linux/skbuff.h:2521
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
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err_encap
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b6ae41)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b6dfc9)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b70057)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b749b9)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78c4a)
Location: include/linux/skbuff.h:2521
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
In net/ipv6/exthdrs.c (ffffffff81b7a6b5)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:seg6_update_csum
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b7e139)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81b80455)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b86d23)
Location: include/linux/skbuff.h:2521
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87695)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b87ffb)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b8842a)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81b88d91)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81b8aa65)
Location: include/linux/skbuff.h:2521
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
Location: include/linux/skbuff.h:2521
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
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ff30)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b907ee)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b915ae)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91a68)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b91d5c)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81b91fdb)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92a61)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b92fa5)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b942b4)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
```
In net/packet/af_packet.c (ffffffff81b973d8)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81ba08ef)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4f90)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81bb034b)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff81bb0a35)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff81bb1fe4)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
```
In net/mptcp/subflow.c (ffffffff81bc136b)
Location: include/linux/skbuff.h:2521
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
In kernel/bpf/core.c (ffffffff811f943b)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff812396ba)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff814d7ecb)
Location: include/linux/skbuff.h:2537
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff814f52e5)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814fa5b2)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff814ff709)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819d686a)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff819e1537)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819eeb53)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff819f904d)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a0febc)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a1db29)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff81a26537)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81a2e424)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81a36549)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81a38b2a)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/sched/sch_frag.c (ffffffff81a57f04)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/bpf/test_run.c (ffffffff81a71919)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81a84c2e)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81a856ca)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a89956)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff81a8cd19)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e528)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81a8eb20)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81a8f675)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff81a945bd)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a98081)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81aa580e)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81aa5f9a)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf63c)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4559)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac57c5)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81ac73ea)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81acf312)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81acfab5)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff81ad245e)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81ad564c)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81adc715)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81adf245)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae3b94)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff81aed9c7)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff81aef6bc)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af0e85)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81afdf0b)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81b03586)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff81b03c33)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b07f34)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b085a5)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b08b4d)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81b08ddb)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0e349)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81b130d8)
Location: include/linux/skbuff.h:2537
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a936)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1beaf)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (ffffffff81b26213)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d2ae)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
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
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81b3ca05)
Location: include/linux/skbuff.h:2537
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
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b5914c)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b5c392)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b5e319)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81b634dd)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6779c)
Location: include/linux/skbuff.h:2537
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
In net/ipv6/exthdrs.c (ffffffff81b69105)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b6cd19)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f055)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b759e1)
Location: include/linux/skbuff.h:2537
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b76345)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76d2b)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b7715a)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81b77bb1)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81b798c9)
Location: include/linux/skbuff.h:2537
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
Location: include/linux/skbuff.h:2537
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
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f061)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fa1c)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b807a6)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80cb9)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff81b80fb0)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81b8126b)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81bb9)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b820f5)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b833c0)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81b863d4)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81b8f9bf)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b940d0)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81b9f44b)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff81b9fb35)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba1004)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
```
In net/mptcp/subflow.c (ffffffff81bb1d1b)
Location: include/linux/skbuff.h:2537
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
In kernel/bpf/core.c (ffffffff8122aacb)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff81273ec3)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff81530e8b)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff8154fce5)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff81555222)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff8155a779)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81a86eba)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81a91977)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81a9fe73)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81aaac2d)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81ac218c)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81ad15c9)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff81adb2b2)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81ae1a96)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81aec21d)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81aeea0a)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_frag.c (ffffffff81b10ed4)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/bpf/test_run.c (ffffffff81b2b030)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f23a)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81b3fdba)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81b444e6)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff81b47e51)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81b49718)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81b49d2f)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81b4a8b5)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff81b4fa3d)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b53511)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81b61b5e)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81b6237a)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d184)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82d4b)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81b83fd5)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81b85c0a)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81b8dd32)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e4d5)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff81b910ae)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81b94483)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81b9baf5)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81b9e725)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba34a4)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff81badd88)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff81bb0c55)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1365)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81bbf19b)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81bc5816)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff81bc5ee3)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bcae34)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb4b5)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81bcba3d)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81bcbccb)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd184d)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd6fd8)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdef48)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81be065f)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm4_prepare_output
  - net/xfrm/xfrm_output.c:xfrm4_prepare_output
```
```
In net/ipv6/af_inet6.c (ffffffff81beccd0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81bf345e)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81bf5010)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81c03356)
Location: include/linux/skbuff.h:2566
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
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81c20725)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81c23ac7)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81c257c9)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81c2af9d)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f3cc)
Location: include/linux/skbuff.h:2566
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
In net/ipv6/exthdrs.c (ffffffff81c30af5)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
```
```
In net/ipv6/datagram.c (ffffffff81c34c26)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81c37115)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff81c38f3d)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81c40405)
Location: include/linux/skbuff.h:2566
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c40db5)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c417db)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81c41bfa)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81c426d1)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81c44573)
Location: include/linux/skbuff.h:2566
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
Location: include/linux/skbuff.h:2566
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
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a8b1)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b2bc)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4c118)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/exthdrs_core.c (ffffffff81c4c7c6)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4ccd9)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff81c4cfd0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81c4d290)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dc09)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e1a5)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f490)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81c52794)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81c5c15f)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c60870)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81c6cbe1)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_intel
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff81c6d3b5)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff81c6ea04)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
```
In net/mptcp/subflow.c (ffffffff81c7fda8)
Location: include/linux/skbuff.h:2566
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
In kernel/bpf/core.c (ffffffff8126c3c4)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff812c2105)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff815c8388)
Location: include/linux/skbuff.h:2935
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff815e90e0)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff815ef03f)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff815f54f5)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81bfc62a)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81c07bb4)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81c15933)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81c23b7d)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81c3c61b)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81c4eebd)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/gro.c (ffffffff81c54bd1)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/netpoll.c (ffffffff81c5c7b5)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81c6580c)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81c6ebb1)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81c718c9)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_frag.c (ffffffff81c97f95)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/bpf/test_run.c (ffffffff81cb5255)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb991)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81ccc648)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81cd110a)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff81cd5103)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6e9b)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81cd7266)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81cd76f5)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff81cdd4c4)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdfc30)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81cf05bd)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81cf160e)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d0f2)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d1332c)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81d14795)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81d15f61)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81d1ee5b)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f6f5)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff81d22e77)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81d25d0c)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81d2d8b5)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81d30a95)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81d35cf4)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff81d40e27)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff81d441a0)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44925)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81d53ef2)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81d5aa58)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff81d5b1ee)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d607a0)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d60f55)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81d6156e)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81d61855)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d679b3)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d968)
Location: include/linux/skbuff.h:2935
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75cb6)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81d776aa)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (ffffffff81d851a0)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c06e)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81d8de5c)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81d9d2fa)
Location: include/linux/skbuff.h:2935
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
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81dbd4bd)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81dc09ef)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81dc2f60)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81dc824d)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd634)
Location: include/linux/skbuff.h:2935
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
Location: include/linux/skbuff.h:2935
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
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
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
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
```
```
In net/ipv6/datagram.c (ffffffff81dd25c9)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81dd4cb5)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff81dd6eb1)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81ddea38)
Location: include/linux/skbuff.h:2935
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf7a5)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddfdbb)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81de04bb)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81de117a)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81de3574)
Location: include/linux/skbuff.h:2935
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
Location: include/linux/skbuff.h:2935
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
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81dea1cb)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deac0b)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec33d)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/exthdrs_core.c (ffffffff81decba0)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded150)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff81ded48a)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81ded7ac)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee2c9)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deea65)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defebb)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81df576d)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81dfdee7)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e02d84)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81e105e1)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_intel
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff81e10de5)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff81e125a2)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
```
In net/mptcp/subflow.c (ffffffff81e257a4)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
```
```
In net/mctp/af_mctp.c (ffffffff81e36f22)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
```
```
In net/mctp/route.c (ffffffff81e3aabf)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_do_fragment_route
  - net/mctp/route.c:mctp_do_fragment_route
  - net/mctp/route.c:mctp_route_output
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_frag_queue
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
In kernel/bpf/core.c (ffffffff812c13e4)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff81326905)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff816754a8)
Location: include/linux/skbuff.h:2827
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff816989c0)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff8169f31f)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff816a5ff8)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81dab52a)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81db7663)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81dc6cf3)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81dd60ed)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81df418b)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81e03f6d)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/gro.c (ffffffff81e0a35c)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/netpoll.c (ffffffff81e12ea5)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81e1c4c9)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81e268f1)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81e299b9)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_frag.c (ffffffff81e53f45)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/bpf/test_run.c (ffffffff81e737b3)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b7e1)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81e8c568)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81e9138a)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff81e955d3)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81e9743b)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81e97887)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81e97d75)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff81e9df88)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9ffd7)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81eb38f1)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81eb5e0e)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2b6c)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed929c)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81eda8c5)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81edcdea)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81ee5f6b)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ee68d5)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff81eea377)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81eed487)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81ef57b5)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81ef8ba5)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81efe2e4)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09bb7)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff81f0d66f)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0d9e5)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f1e0c2)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81f24ec8)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff81f2567e)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f2af60)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2b835)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f2be9e)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81f2c1d5)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f32a13)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38f58)
Location: include/linux/skbuff.h:2827
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81f423f6)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_beet_make_header
  - net/xfrm/xfrm_input.c:xfrm6_extract_header
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43f62)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm6_beet_make_header
  - net/xfrm/xfrm_output.c:xfrm6_extract_header
```
```
In net/ipv6/af_inet6.c (ffffffff81f52be0)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a02e)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bfcc)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81f6c22a)
Location: include/linux/skbuff.h:2827
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
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81f8d9fd)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81f91173)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81f939b0)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81f98fdd)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e747)
Location: include/linux/skbuff.h:2827
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
In net/ipv6/exthdrs.c (ffffffff81f9f6e5)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
```
```
In net/ipv6/datagram.c (ffffffff81fa3a49)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6375)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff81fa8871)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81fb0c2c)
Location: include/linux/skbuff.h:2827
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1a65)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb20db)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81fb284b)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff81fb35da)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81fb5bf4)
Location: include/linux/skbuff.h:2827
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
Location: include/linux/skbuff.h:2827
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
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81fbda8b)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe7cb)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbff8d)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/exthdrs_core.c (ffffffff81fc0990)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc0f60)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff81fc12aa)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff81fc15dc)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc284e)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2aa5)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3fdb)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81fc960a)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81fd2aa7)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd7ca4)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81fe6cf1)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_intel
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff81fe75e5)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff81fe9012)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
```
In net/mptcp/subflow.c (ffffffff81ffd3f4)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
```
```
In net/mctp/af_mctp.c (ffffffff82010942)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
```
```
In net/mctp/route.c (ffffffff8201408f)
Location: include/linux/skbuff.h:2827
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_do_fragment_route
  - net/mctp/route.c:mctp_do_fragment_route
  - net/mctp/route.c:mctp_route_output
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_frag_queue
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
In kernel/bpf/core.c (ffffffff812e81b4)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff81356c56)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff816ad828)
Location: include/linux/skbuff.h:2881
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff816d0e69)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff816d8106)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff816de9d8)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81e1b02a)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81e27fa6)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81e3609e)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81e46f2d)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81e65d9b)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81e7675a)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/gso.c (ffffffff81e7d852)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_validate_network_len
```
```
In net/core/netpoll.c (ffffffff81e867d4)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81e90889)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81e9be91)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81e9effa)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_frag.c (ffffffff81eaf7c5)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/bpf/test_run.c (ffffffff81ecf668)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81ee982b)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81eea671)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81eefb0a)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff81ef3dd3)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5c6b)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81ef60c4)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81ef65d5)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff81efc752)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe827)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81f1209e)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81f1422e)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31853)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f38386)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81f399a5)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff81f3c03a)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81f4576b)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81f46115)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff81f49ca7)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81f4ce47)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81f55165)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81f58615)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5dd77)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff81f696c7)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff81f6d2d3)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6d685)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f7dbb2)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81f84a61)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff81f8520e)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8ac30)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b4b5)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f8bb3e)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81f8be8c)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f93b66)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session6
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81f987e1)
Location: include/linux/skbuff.h:2881
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1c2c)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_beet_make_header
  - net/xfrm/xfrm_input.c:xfrm6_extract_header
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa4619)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm6_beet_make_header
  - net/xfrm/xfrm_output.c:xfrm6_extract_header
```
```
In net/ipv6/af_inet6.c (ffffffff81fb25d3)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9cdf)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81fbbd7c)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81fcc365)
Location: include/linux/skbuff.h:2881
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
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81fee1d9)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81ff1a36)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81ff4309)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81ff99ad)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81fff203)
Location: include/linux/skbuff.h:2881
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
In net/ipv6/exthdrs.c (ffffffff82000245)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
```
```
In net/ipv6/datagram.c (ffffffff82004181)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff82006bf5)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff82009201)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff820112e2)
Location: include/linux/skbuff.h:2881
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012145)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff820127e8)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff82012f60)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff82013cc7)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff82016305)
Location: include/linux/skbuff.h:2881
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
Location: include/linux/skbuff.h:2881
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
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201eaab)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f66b)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020f0b)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/exthdrs_core.c (ffffffff82021910)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff82021ef0)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff8202222a)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff8202255c)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/ipv6/ip6_offload.c (ffffffff820237cc)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023a35)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024ffb)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff8202bc01)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff8204e6fa)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82053994)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82062f41)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff82063845)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff82065292)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
```
In net/mptcp/subflow.c (ffffffff820796c4)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
```
```
In net/mctp/af_mctp.c (ffffffff8208d0f2)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
```
```
In net/mctp/route.c (ffffffff82090f0f)
Location: include/linux/skbuff.h:2881
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_do_fragment_route
  - net/mctp/route.c:mctp_do_fragment_route
  - net/mctp/route.c:mctp_route_output
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_frag_queue
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
In kernel/bpf/core.c (ffffffff81306504)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff8137f786)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff816ea8b8)
Location: include/linux/skbuff.h:2888
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff8170d489)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff81714393)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff8171b5a8)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81ed85ea)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_update_lse
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/flow_dissector.c (ffffffff81ee6029)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81ef435e)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81f05bed)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81f24f4b)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:bpf_skb_load_bytes_relative
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81f3671d)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/gso.c (ffffffff81f3e7c2)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_validate_network_len
```
```
In net/core/netpoll.c (ffffffff81f487e1)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81f52c59)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81f5e5f1)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81f6176a)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_frag.c (ffffffff81f72245)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_frag_prepare_frag
```
```
In net/bpf/test_run.c (ffffffff81f92fb8)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81fad54c)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81fae421)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_ip6_check_hbh_len
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81fb3c5a)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff81fb7d63)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9c1b)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81fba054)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81fba565)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff81fc0692)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc2a4a)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81fcf5c6)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81fd870e)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_rcv_spurious_retrans
  - net/ipv4/tcp_input.c:tcp_rcv_spurious_retrans
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7a4e)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_ao_sign_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe446)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffa95)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff8200215b)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8200b8bb)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8200c255)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff8200fdc7)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff82012f57)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff8201b3d5)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8201ead5)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff82024337)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff8202fd47)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff82033a27)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82033dd5)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_parse_protocol
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff820443f2)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff8204b2c4)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff8204b8be)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82052340)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052bb5)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8205343e)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff8205378c)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/ipv4/tcp_ao.c (ffffffff820589b7)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_ao_prepare_reset
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_calc_key_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff82065b51)
Location: include/linux/skbuff.h:2888
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f06e)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_beet_make_header
  - net/xfrm/xfrm_input.c:xfrm6_extract_header
```
```
In net/xfrm/xfrm_output.c (ffffffff82071957)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm6_beet_make_header
  - net/xfrm/xfrm_output.c:xfrm6_extract_header
```
```
In net/ipv6/af_inet6.c (ffffffff8207fd63)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff820871b1)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff820891ac)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff82099b48)
Location: include/linux/skbuff.h:2888
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
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff820bbdb0)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff820bf635)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff820c125a)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff820c761d)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cdf13)
Location: include/linux/skbuff.h:2888
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
In net/ipv6/exthdrs.c (ffffffff820cefd5)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
```
```
In net/ipv6/datagram.c (ffffffff820d2f41)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff820d5a55)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ioam6.c (ffffffff820d81a1)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff820e0272)
Location: include/linux/skbuff.h:2888
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e12b5)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e1966)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff820e20c0)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/netfilter.c (ffffffff820e2e24)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff820e542e)
Location: include/linux/skbuff.h:2888
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
Location: include/linux/skbuff.h:2888
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
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820edbdb)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/seg6_local.c:input_action_end_x_core
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee79b)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820f0038)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/exthdrs_core.c (ffffffff820f0a30)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f1010)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/ip6_icmp.c (ffffffff820f134a)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/output_core.c (ffffffff820f167c)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2882)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2b95)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f42db)
Location: include/linux/skbuff.h:2888
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
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ipv6/tcp_ao.c:tcp_v6_ao_calc_key_skb
```
```
In net/packet/af_packet.c (ffffffff820fb6b2)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff82120d7a)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82126184)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82136081)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gmcma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff82136985)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff82138432)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
```
In net/mptcp/subflow.c (ffffffff8214eb14)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
```
```
In net/mctp/af_mctp.c (ffffffff821635b3)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
```
```
In net/mctp/route.c (ffffffff8216742f)
Location: include/linux/skbuff.h:2888
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_do_fragment_route
  - net/mctp/route.c:mctp_do_fragment_route
  - net/mctp/route.c:mctp_route_output
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_frag_queue
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
In kernel/bpf/core.c (ffff80001025d590)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffff80001028e898)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffff80001054e9c4)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In security/selinux/netlabel.c (ffff80001056c5b4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffff800010571948)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffff80001057786c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e602c)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/core/skbuff.c (ffff800010bb94a0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffff800010bc3d84)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffff800010bcff9c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffff800010be1b44)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffff800010bf726c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/tso.c (ffff800010c04a60)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffff800010c115c4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffff800010c19d84)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffff800010c1f318)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffff800010c55ecc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffff800010c56cec)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffff800010c5aa6c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffff800010c5ed70)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffff800010c5fdb0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffff800010c602d4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffff800010c60db4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffff800010c659f8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffff800010c69578)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffff800010c7abe4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e8f8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c932e8)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffff800010c95174)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffff800010c9649c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffff800010c9f6f4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffff800010ca00b8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffff800010ca22d8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffff800010ca50d4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffff800010cab7c4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffff800010cae5f8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffff800010cb4c20)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffff800010cbec18)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffff800010cc00e0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc2504)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffff800010cd0068)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffff800010cd20ac)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffff800010cd2654)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd6f00)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_state.c (ffff800010cd7660)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7788)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7f74)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdb4ac)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffff800010ce33c4)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffff800010ceaa30)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010ceb770)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (ffff800010cf5730)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffff800010cfc360)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv6/ip6_input.c (ffff800010cfdf98)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffff800010d11edc)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
In net/ipv6/udp.c (ffff800010d244cc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffff800010d29c2c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffff800010d2cd50)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d2ff6c)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38ec8)
Location: include/linux/skbuff.h:2477
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
In net/ipv6/exthdrs.c (ffff800010d3aac4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffff800010d3da78)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffff800010d40bb0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffff800010d480a8)
Location: include/linux/skbuff.h:2477
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffff800010d48d58)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffff800010d48e54)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffff800010d4993c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffff800010d4a420)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffff800010d4c628)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffff800010d517c8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffff800010d52884)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffff800010d53298)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffff800010d53820)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffff800010d53e60)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffff800010d54a90)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d54fc4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffff800010d562e0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffff800010d57cfc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffff800010d642e8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d69440)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffff800010d76f4c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
```
```
In net/ncsi/ncsi-aen.c (ffff800010d77ba4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffff800010d797d8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
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
In kernel/bpf/core.c (c0490e34)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (c04bda8c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (c070836c)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In security/selinux/netlabel.c (c071fe20)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (c0724c08)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (c072a694)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac9378)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/core/skbuff.c (c0cd5f44)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (c0cdf220)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (c0ce8e64)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (c0cfcb40)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (c0d10360)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/tso.c (c0d1decc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (c0d2946c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (c0d2f5d0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (c0d36ec4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (c0d658dc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (c0d663f8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (c0d67ee0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_multipath_l3_keys
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (c0d6d918)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (c0d6f588)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (c0d6fb84)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (c0d7077c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (c0d7565c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (c0d78788)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (c0d88278)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (c0d9dee0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (c0da1dd8)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/ipv4/tcp_offload.c (c0da38b4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (c0da5748)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0daca1c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (c0dad01c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (c0daf0ac)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (c0db19ac)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (c0db8694)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (c0dbc8e8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (c0dc05d4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (c0dca39c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (c0dcc5d0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (c0dcddf0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (c0dda610)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (c0ddbf3c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (c0ddc574)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (c0de0c10)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_state.c (c0de118c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (c0de12b0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (c0de1a28)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (c0de5e18)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (c0dec9ac)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/xfrm/xfrm_input.c (c0df2a40)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_output.c (c0df3650)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (c0dfc178)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (c0e03754)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv6/ip6_input.c (c0e05918)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (c0e12cc8)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (c0e2d9c0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c0e30d6c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e338a8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c0e37a90)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c0e3ba68)
Location: include/linux/skbuff.h:2477
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
In net/ipv6/exthdrs.c (c0e3cfe0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (c0e41038)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (c0e43588)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (c0e49ab8)
Location: include/linux/skbuff.h:2477
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (c0e4a200)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (c0e4a2c4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (c0e4acb4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (c0e4ba2c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (c0e4d8d8)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c0e5236c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (c0e52d5c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (c0e53c14)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (c0e54100)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (c0e54604)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (c0e55094)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (c0e5556c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c0e568dc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (c0e59c8c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (c0e62f04)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (c0e67b34)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (c0e736a4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (c0e73e70)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (c0e751cc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
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
In kernel/bpf/core.c (c000000000301fcc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (c00000000033b0d4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (c0000000006afa78)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In security/selinux/netlabel.c (c0000000006d0878)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (c0000000006d8774)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (c0000000006e0ec0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (c000000000c91a50)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (c000000000c9e090)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (c000000000caccc4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (c000000000cc2eac)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (c000000000cdccd0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/tso.c (c000000000ceea08)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (c000000000cfe2c4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (c000000000d06838)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (c000000000d111c0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (c000000000d56750)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (c000000000d57974)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (c000000000d5c674)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (c000000000d60c58)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (c000000000d62b30)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (c000000000d631d8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (c000000000d6402c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (c000000000d6a158)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e1dc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (c000000000d7f984)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d320)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (c000000000da3860)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/ipv4/tcp_offload.c (c000000000da60f4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (c000000000da7da8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c000000000db21c8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (c000000000db2b50)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (c000000000db5830)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (c000000000db8df8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (c000000000dc20f8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (c000000000dc69c4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (c000000000dcbe70)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (c000000000dd9330)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (c000000000ddb4bc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dddc30)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (c000000000dee30c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (c000000000df0484)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (c000000000df0c24)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (c000000000df6c34)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_state.c (c000000000df7468)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (c000000000df75fc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (c000000000df80b0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (c000000000e004dc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (c000000000e06acc)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/xfrm/xfrm_input.c (c000000000e0e6c4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e0f574)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (c000000000e1b8e8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (c000000000e23e40)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv6/ip6_input.c (c000000000e2611c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (c000000000e37f10)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
In net/ipv6/udp.c (c000000000e56d50)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (c000000000e5aa40)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c000000000e5e7fc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c000000000e61328)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c39c)
Location: include/linux/skbuff.h:2477
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
In net/ipv6/exthdrs.c (c000000000e6df00)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (c000000000e722e0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (c000000000e752a8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (c000000000e7d594)
Location: include/linux/skbuff.h:2477
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (c000000000e7e108)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e20c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (c000000000e7f014)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (c000000000e80490)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (c000000000e82ce0)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c000000000e89a20)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (c000000000e8af4c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (c000000000e8b9a8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (c000000000e8c028)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (c000000000e8c7a8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (c000000000e8d614)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8dcc4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f498)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (c000000000e92db4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (c000000000e9fbe8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea6330)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (c000000000eb6c64)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
```
```
In net/ncsi/ncsi-aen.c (c000000000eb75f0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (c000000000eb900c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
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
In kernel/bpf/core.c (ffffffe00019bc20)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffe0001c1a54)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffe0003a8abe)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In security/selinux/netlabel.c (ffffffe0003c106a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffe0003c5ab8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffe0003c9d78)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffe0007489fa)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffffffe0007507e0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffe00075a0b8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffe00076890e)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffe0007790b6)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/tso.c (ffffffe000783614)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffe00078d786)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffe0007910ec)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffe000798a7e)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffe0007c027a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffe0007c0c42)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffe0007c3e5c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffe0007c6bda)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c7ed2)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffe0007c8562)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffe0007c8fac)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffe0007cd124)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf452)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffe0007de5ec)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eebfe)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2a7a)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4392)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffe0007f56a6)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_rcv
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffe0007fc232)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffe0007fc80c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffe0007fe324)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffe0008009da)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffe00080644a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffe0008099b8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c7c4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffe0008149a2)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffe000816b64)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe00081796a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffe000822020)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffe00082344c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffe000823994)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008277ea)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_state.c (ffffffe000827d90)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffe000827e8c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffe000828514)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082cde0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffe000831bfe)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffe0008385ba)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe0008390e8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (ffffffe000841142)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffe000846c32)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv6/ip6_input.c (ffffffe0008482dc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffe000853ece)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
In net/ipv6/udp.c (ffffffe000867ffc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffe00086a450)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffe00086cf68)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffe00086f6f4)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008762a6)
Location: include/linux/skbuff.h:2477
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
In net/ipv6/exthdrs.c (ffffffe000877686)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffe00087a14a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffe00087c3fa)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffe000881bcc)
Location: include/linux/skbuff.h:2477
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffe0008822b4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffe0008823a8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882d2c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffe00088392a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffe00088535c)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffe0008899ba)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a882)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffe00088aff2)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b500)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffe00088b9a2)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c416)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c842)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088db98)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffe00088f9ce)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffe00089837c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089c4bc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffe0008a6dea)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
```
```
In net/ncsi/ncsi-aen.c (ffffffe0008a74c6)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffe0008a867c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
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
In kernel/bpf/core.c (ffffffff811d5208)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff811fdf45)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff81459891)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff814740a5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814787cb)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff8147d949)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818bec96)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffffffff818c792b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818d16f3)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff818e20ed)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff818f544c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/tso.c (ffffffff81901151)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff8190af3b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81911325)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff819184fb)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff819464b5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff8194701a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff8194a526)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff8194e67c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff8194f438)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff8194fa8a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81950605)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff819550d0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff8195805c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff81964957)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197bb19)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f840)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81980fb5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff819824a3)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81989d64)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8198a375)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff8198c590)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff8198f00c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff819958d5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81998ba5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff8199c584)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff819a59e7)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff819a6f6c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8f8a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819b43a5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff819b5a27)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff819b60a2)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819ba524)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_state.c (ffffffff819baab5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff819baba5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb32d)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffff819beba6)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff819c5478)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb605)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc18c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (ffffffff819d4453)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff819da8b3)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv6/ip6_input.c (ffffffff819dc18c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819e8e41)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
In net/ipv6/udp.c (ffffffff81a008f0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a03206)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a0643c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a07c9c)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10078)
Location: include/linux/skbuff.h:2477
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
In net/ipv6/exthdrs.c (ffffffff81a11735)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a14a5d)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a16bb5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a1ca88)
Location: include/linux/skbuff.h:2477
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a1d185)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d225)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1db5c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff81a1e812)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a2043b)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a24da9)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a2563e)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a2629e)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a26751)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff81a26bfb)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81a27590)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27acc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28b50)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffff81a2bbc3)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81a349b4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a38e77)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a4422b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff81a449e5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a45c74)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
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
In kernel/bpf/core.c (ffffffff811c7fc8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff811f0c95)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff8144a2c1)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff81464ac5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814691eb)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff8146e369)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/vxlan.c (ffffffff81773c34)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/skbuff.c (ffffffff81878bd6)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffffffff8188186b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff8188b583)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff8189bf2d)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff818af27c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/tso.c (ffffffff818baf81)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff818c4cd6)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff818cb0e5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff818d22ab)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff818fffa5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff81900b0a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81904016)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff8190816c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81908f28)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff8190957a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff8190a0f5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff8190ebc0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911b4c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff8191e447)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819355d9)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939300)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff8193aa75)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff8193bf63)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81943824)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81943e35)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81946050)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81948acc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8194f395)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81952665)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81956044)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f4a7)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff81960a2c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962a4a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ip_tunnel.c (ffffffff8196782f)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv4/ipmr.c (ffffffff819709d5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/udp_tunnel.c (0)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81972817)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff81972e92)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81977314)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_state.c (ffffffff819778a5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977995)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197811d)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197b996)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff81982268)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff819883f5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81988f7c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (ffffffff81991213)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81997673)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv6/ip6_input.c (ffffffff81998f4c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819a5c01)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
In net/ipv6/udp.c (ffffffff819bd6b0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff819bffc6)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff819c31fc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c4a5c)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cce38)
Location: include/linux/skbuff.h:2477
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
In net/ipv6/exthdrs.c (ffffffff819ce4f5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff819d181d)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff819d3975)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff819d9848)
Location: include/linux/skbuff.h:2477
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffff819d9f45)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d9fe5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff819da91c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff819db5d2)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff819dd1fb)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819e1b69)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e23fe)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffff819e305e)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e3511)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff819e39bb)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4350)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e488c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/ip6_udp_tunnel.c (ffffffff819e5abf)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_udp_tunnel.c:udp_tunnel6_xmit_skb
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5d40)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffff819e8db3)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff819f15d4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f5a97)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a00e1b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff81a015d5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a02864)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
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
In kernel/bpf/core.c (ffffffff811d2fd8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff811fbd15)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff81455931)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff81470145)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff8147486b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff814799e9)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8190fc96)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffffffff8191892b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819226f3)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff8193311d)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff8194647c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/tso.c (ffffffff81952181)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff8195bf6b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81962355)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff8196968b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff81997645)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff819981aa)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199f5ee)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_update
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_update
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a49b4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:ipv4_confirm
```
```
In net/netfilter/nf_conntrack_proto_icmp.c (ffffffff819a7b19)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_icmpv4_error
```
```
In net/netfilter/nf_conntrack_seqadj.c (ffffffff819a84e4)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/netfilter/nf_conntrack_proto_icmpv6.c (ffffffff819a89a2)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmpv6.c:nf_conntrack_icmpv6_error
```
```
In net/ipv4/route.c (ffffffff819b4cf6)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff819b8e4c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9c08)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819ba25a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff819badd5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff819bf8a0)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c282c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff819cf127)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e62e9)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819ea010)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819eb785)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff819ecc73)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819f4534)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819f4b45)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff819f6da4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff819f98ac)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81a00175)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81a03445)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06e24)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10287)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff81a1180c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1382a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a1ec45)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81a202c7)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff81a20942)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/netfilter/nf_defrag_ipv4.c (ffffffff81a20bd9)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a24fa4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_state.c (ffffffff81a25535)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a25625)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25dad)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a29626)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2fef8)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81a36085)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36c0c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (ffffffff81a3eed3)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81a45333)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv6/ip6_input.c (ffffffff81a46c0c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a538c1)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
In net/ipv6/udp.c (ffffffff81a6b370)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a6dc86)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a70ebc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a7271c)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7aaf8)
Location: include/linux/skbuff.h:2477
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
In net/ipv6/exthdrs.c (ffffffff81a7c1b5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a7f4dd)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a81635)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a87508)
Location: include/linux/skbuff.h:2477
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a87c05)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a87ca5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a885dc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff81a89292)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a8aebb)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f829)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a900be)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a910de)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a91e4e)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a92301)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff81a927ab)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81a93140)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9367c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a94700)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffff81a97773)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81aa0864)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa4d27)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81ab00db)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff81ab0895)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ab1b24)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
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
In kernel/bpf/core.c (ffffffff811e12c8)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_internal_load_pointer_neg_helper
```
```
In kernel/bpf/cgroup.c (ffffffff8120a8f5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In security/selinux/hooks.c (ffffffff81470c21)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff814879b5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff8148c1e2)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff81491499)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81930dc6)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_dec_ttl
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_pop
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/flow_dissector.c (ffffffff81939570)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff819438c3)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81954a4d)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81967d6c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes_relative
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_skb_load_bytes_relative
```
```
In net/core/tso.c (ffffffff81973bc1)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff8197e34b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff819845c5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/lwt_bpf.c (ffffffff8198ba6b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff819ba325)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff819bae8a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819be436)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_bug
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (ffffffff819c26fe)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff819c3648)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819c3b4a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff819c46d5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:ip_options_fragment
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:__ip_options_echo
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/ip_output.c (ffffffff819c921f)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc22c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_input.c (ffffffff819d8cb7)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819effa9)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_ts_off
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3e40)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5635)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (ffffffff819f6b63)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819fe6f4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff819fed15)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/arp.c (ffffffff81a00fc4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81a03b9c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81a0a1c5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81a0d995)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81a114d4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1aad7)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
```
In net/ipv4/ping.c (ffffffff81a1c17c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e1fa)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a2a101)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81a2b7c7)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff81a2be62)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a30414)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_state.c (ffffffff81a309b5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30aa5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a3125d)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a34bb6)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3b878)
Location: include/linux/skbuff.h:2477
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81a419f7)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a4259c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/af_inet6.c (ffffffff81a4a993)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/ip6_output.c (ffffffff81a51003)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv6/ip6_input.c (ffffffff81a5297e)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a5f8b1)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
In net/ipv6/udp.c (ffffffff81a77980)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a7a2a6)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a7d4cc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a7eda6)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87338)
Location: include/linux/skbuff.h:2477
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
In net/ipv6/exthdrs.c (ffffffff81a88a05)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_calipso
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_ra
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a8bd9d)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a8df35)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (ffffffff81a940de)
Location: include/linux/skbuff.h:2477
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
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_state.c (ffffffff81a94835)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_extract_header
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a948d5)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_rcv_tnl
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a9522c)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_error
  - net/ipv6/xfrm6_output.c:xfrm6_local_rxpmtu
```
```
In net/ipv6/netfilter.c (ffffffff81a95ef2)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a97b19)
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
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
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c5a9)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d31a)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a9defe)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_tlv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e3b1)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/output_core.c (ffffffff81a9e88f)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ip6_find_1stfragopt
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f2da)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f7cc)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0860)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
```
In net/packet/af_packet.c (ffffffff81aa4093)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81aacae7)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab10a3)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81abc48b)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_mlx
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-rsp.c:ncsi_validate_rsp_pkt
```
```
In net/ncsi/ncsi-aen.c (ffffffff81abcc45)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler
```
```
In net/ncsi/ncsi-manage.c (ffffffff81abded4)
Location: include/linux/skbuff.h:2477
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
</details>
</li>
</ul>

## Differences
