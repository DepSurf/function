# Function: <code>ip_hdr</code>

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
In security/smack/smack_lsm.c (0)
Location: include/linux/ip.h:23
Inline: True
```
```
In security/lsm_audit.c (ffffffff813661c6)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81709786)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/tso.c (0)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/core/netpoll.c (ffffffff81739490)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/route.c (ffffffff81753384)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff8175a89c)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff8175b3a7)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8175c712)
Location: include/linux/ip.h:23
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
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761a77)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177a9f4)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81783175)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff8178512a)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8178a04c)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (0)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8178e1d1)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff817949e8)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8179626e)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/fib_frontend.c (ffffffff8179aaab)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (0)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a482c)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff817a741e)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_get_route
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff817ac188)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817ae095)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff817afd45)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff817afdbb)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff817b020a)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_state.c (ffffffff817b7ff8)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/ip.h:23
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
In security/smack/smack_lsm.c (ffffffff813982f7)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff8139c2a6)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81771698)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff81784eb5)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/tso.c (ffffffff8179fd31)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff817a5744)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/route.c (ffffffff817c3554)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff817c6bb3)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff817c76ab)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff817cb951)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb870)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0705)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff817f1bea)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff817f7f50)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffff817f9a91)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff817fc5fa)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/af_inet.c (ffffffff81802377)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81805965)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff818086db)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81810634)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818124dc)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818187d4)
Location: include/linux/ip.h:23
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81818f89)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff818197d9)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181c07b)
Location: include/linux/ip.h:23
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
In net/ipv4/xfrm4_policy.c (ffffffff8181c5f1)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff8181cc75)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181cd35)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8181d2f5)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_state.c (ffffffff81825208)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv6/udp.c (ffffffff8185137f)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff818565c9)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/datagram.c (ffffffff81864887)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/netlabel/netlabel_kapi.c (ffffffff8187ded8)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818822f7)
Location: include/linux/ip.h:23
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
In security/smack/smack_lsm.c (ffffffff813aeed7)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff813b2e56)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8179e753)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff817b24d7)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/tso.c (ffffffff817ce701)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff817d41b4)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/route.c (ffffffff817f2b46)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff817f66b3)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff817f719b)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff817fb5b3)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c1e0)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81821475)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff818229da)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81828df0)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffff8182a961)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff8182d55a)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/af_inet.c (ffffffff81833309)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81836db5)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff8183978b)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81841b34)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818439e0)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8184a034)
Location: include/linux/ip.h:23
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff8184a7e9)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/netfilter.c (ffffffff8184b099)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184d93b)
Location: include/linux/ip.h:23
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
In net/ipv4/xfrm4_policy.c (ffffffff8184dea8)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff8184e545)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e605)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8184eba5)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_state.c (ffffffff81856b68)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81883382)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff818883b9)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/datagram.c (ffffffff81896f7a)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/netlabel/netlabel_kapi.c (ffffffff818b2788)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b6ba7)
Location: include/linux/ip.h:23
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
In security/smack/smack_lsm.c (ffffffff813c547c)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff813c9826)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff817bc3a0)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff817cfcce)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/tso.c (ffffffff817edbb1)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff817f34fd)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/route.c (ffffffff818134ea)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81816acd)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81817576)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff8181b985)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cc40)
Location: include/linux/ip.h:23
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
In net/ipv4/tcp_fastopen.c (ffffffff8184136a)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81842155)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff8184365c)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8184a0d0)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffff8184bb3f)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff8184ea2e)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81854668)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81856d79)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff8185acfb)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff818632ec)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8186523f)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8186da89)
Location: include/linux/ip.h:23
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff8186e191)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8187139b)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff818718f8)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff81871f75)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81872035)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8187274c)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_state.c (ffffffff8187a4e3)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv6/udp.c (ffffffff818a8047)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff818aea97)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (ffffffff818d9138)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dd487)
Location: include/linux/ip.h:23
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
In security/smack/smack_lsm.c (ffffffff813eb54c)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff813efcb6)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81836a70)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff81849621)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/tso.c (ffffffff81869df1)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff8186e8ed)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/route.c (ffffffff81892b3a)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81895c8d)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81896736)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff8189a8be)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc5ec)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1a2e)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff818c303c)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff818c9c7d)
Location: include/linux/ip.h:23
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
In net/ipv4/udp_offload.c (ffffffff818ca765)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffff818cb7df)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff818ce777)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff818d4508)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff818d6c29)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff818dac2b)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff818e3428)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e539f)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818ee3c9)
Location: include/linux/ip.h:23
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff818eeb21)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f1d8b)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff818f22b8)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff818f2935)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2a15)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f314c)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_state.c (ffffffff818faf53)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv6/udp.c (ffffffff8192aaf7)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81931757)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff8194fb32)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffffffff8195ed28)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81963077)
Location: include/linux/ip.h:23
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
In security/selinux/netlabel.c (ffffffff81417d48)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff8141ce84)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff81421265)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81880bc6)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff81893605)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/tso.c (ffffffff818b9ac1)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff818bfa79)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/nf_queue.c (ffffffff818e15c2)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff818e480c)
Location: include/linux/ip.h:23
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
In net/ipv4/ip_input.c (ffffffff818e868c)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff818e9f4d)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff818ea9c5)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff818eedab)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81912243)
Location: include/linux/ip.h:23
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
In net/ipv4/tcp_fastopen.c (ffffffff81916641)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff819176f5)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff81918b16)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8191fd23)
Location: include/linux/ip.h:23
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
In net/ipv4/udp_offload.c (ffffffff819202c5)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffff81921cdf)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff8192509b)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8192abeb)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8192df0b)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81931bf3)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81939d56)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193bc6d)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81943fb5)
Location: include/linux/ip.h:23
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff8194543c)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv4/netfilter.c:nf_ip_checksum
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81948687)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81948bf5)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff81949275)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81949355)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81949a7d)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_state.c (ffffffff81951a73)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81983207)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff8198a273)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819a89ea)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffffffff819b84f9)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bc887)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff81434274)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814387bb)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff8143d905)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818a1a75)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff818b402c)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/tso.c (ffffffff818e0881)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff818e8899)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/nf_queue.c (ffffffff8190e144)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff8190eadb)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81911736)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81916073)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff8191736f)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81917735)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff8191c59a)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940a20)
Location: include/linux/ip.h:23
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
In net/ipv4/tcp_fastopen.c (ffffffff81944de1)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81945e35)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff819472e3)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8194e98d)
Location: include/linux/ip.h:23
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
In net/ipv4/udp_offload.c (ffffffff8194efe5)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffff81950b08)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81953ea7)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8195a375)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8195d7b5)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81961453)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff819699e7)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bac6)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81974105)
Location: include/linux/ip.h:23
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff819757e2)
Location: include/linux/ip.h:23
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
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197a364)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_optptr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8197a8c5)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv4/xfrm4_state.c (ffffffff8197af25)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b005)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b73d)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_state.c (ffffffff81984d13)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819b96c9)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff819c0b1d)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca4ce)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:23
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819df514)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffffffff819ef7c9)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f3ad7)
Location: include/linux/ip.h:23
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff81461d15)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff8146640b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff8146b4c5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818ec4d4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff819008b1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/core/tso.c (ffffffff8192ef11)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff819380ab)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81943730)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff8196fc88)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff819707ba)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81973c96)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
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
In net/ipv4/ip_input.c (ffffffff81977e9c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81978c58)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819792aa)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81979e35)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff8197e8c0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4fa9)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa465)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff819ab963)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819b3174)
Location: include/linux/ip.h:19
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
In net/ipv4/udp_offload.c (ffffffff819b37d5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffff819b53d3)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff819b87c2)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff819beef5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff819c2414)
Location: include/linux/ip.h:19
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
In net/ipv4/fib_frontend.c (ffffffff819c5c34)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff819d067c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d27ea)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819ddbd5)
Location: include/linux/ip.h:19
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff819df301)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e3ea4)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e4505)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4c7d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e8653)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff819eef53)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4cd7)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6185)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (ffffffff81a28356)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81a2f813)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a390df)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e0bc)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81a5ea2b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a62f07)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff8147bac5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814801eb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff814852a5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8191e604)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff81932be1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/core/tso.c (ffffffff81961181)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff8196af6b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff8197872b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff819a668e)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff819a71aa)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819aa6b6)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
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
In net/ipv4/ip_input.c (ffffffff819ae80c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff819af5c8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819afc1a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff819b0795)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff819b5260)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbca9)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1135)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff819e2633)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819e9ef4)
Location: include/linux/ip.h:19
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
In net/ipv4/udp_offload.c (ffffffff819ea505)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffff819ec0f3)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff819ef4c2)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff819f5b35)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff819f8fb4)
Location: include/linux/ip.h:19
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
In net/ipv4/fib_frontend.c (ffffffff819fc7e4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81a071cc)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a091ea)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a14d1d)
Location: include/linux/ip.h:19
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81a16397)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a1ae94)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b515)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1bc9d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1f663)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25e23)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b987)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2ce05)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (ffffffff81a5ede2)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81a66363)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6fc4f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a84ce8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81a9565b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a99ae7)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff814d1075)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814d6853)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff814db445)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819f1e19)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff81a07b9a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/core/tso.c (ffffffff81a34694)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff81a3ecd4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81a4d6d1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f9ce)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81a9050a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a949f6)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
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
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81a99aea)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81a9a625)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff81a9f4bb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac85d6)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ace725)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff81ad046a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81ad7ad2)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad81d5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
```
```
In net/ipv4/arp.c (ffffffff81ad9e59)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81add412)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81ae4025)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81ae6ca9)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeb574)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81af77cc)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8c77)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b05c9d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81b073a9)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0befb)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b0cb5d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81b0cdeb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12285)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17533)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e320)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f302)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/ipv6/udp.c (ffffffff81b5831f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81b5ed5e)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69b91)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81b8008c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81b90c6b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b95327)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff814ee585)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814f3602)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff814f88d5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819f1ab9)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff81a0925a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff81a311c1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/tso.c (ffffffff81a369ad)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff81a41a74)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81a53398)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/bpf/test_run.c (ffffffff81a8888b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81a999be)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81a9a3da)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a9e9f6)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
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
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3a3a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81aa4585)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff81aa93fb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4576)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ada745)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff81adc47a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81ae4122)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4875)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff81ae68be)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81c32830)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81af0f55)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81af3b79)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:ip_mc_check_iphdr
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/fib_frontend.c (ffffffff81af8474)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81b046ac)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06d02)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b13ecd)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81b15777)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b1a28b)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b1ae9d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81b1b12b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b206d5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81b255f3)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2cbea)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2dbd2)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/ipv6/udp.c (ffffffff81b6697a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81b6d4de)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78663)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f247)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81ba0947)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4f90)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff814f52e5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814fa5b2)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff814ff645)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819d6d39)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff819efbea)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff81a18201)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/tso.c (ffffffff81a1db29)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff81a26537)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81a36549)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81a38bc5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/bpf/test_run.c (ffffffff81a71aeb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81a84cce)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81a856ca)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81a89956)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
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
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81a8eb20)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81a8f675)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff81a945bd)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81aa586a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf63c)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac57c5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff81ac73ea)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81acf312)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81acfab5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff81ad1b8f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81c24b02)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81adc715)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81adf27f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81aef6bc)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af244c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b01d13)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81b03586)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b07f34)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81b08b4d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81b08ddb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0d215)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81b13113)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a825)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c22a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (ffffffff81b54b84)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81b5b874)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b675ab)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ec07)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81b8fa17)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b940d0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff8154fce5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff81555222)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff8155a6b5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81a87389)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff81aa100a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff81acb93e)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/tso.c (ffffffff81ad15c9)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff81adb2b2)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81ae1a05)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
```
```
In net/core/selftests.c (ffffffff81aec21d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81aeeaa1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/bpf/test_run.c (ffffffff81b2b202)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f2c4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81b3fdba)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81b444e6)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
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
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81b49d2f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81b4a8b5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff81b4fa3d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81b61bba)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d184)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81b83fd5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff81b85c0a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81b8dd32)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e4d5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff81b907df)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81d3c111)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81b9baf5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81b9e75f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81bb0c55)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb295c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81bc3b13)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81bc5816)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bcae34)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81bcba3d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81bcbccb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd11b5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd7013)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdee45)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81be15c2)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm4_prepare_output
  - net/xfrm/xfrm_output.c:xfrm4_prepare_output
```
```
In net/ipv6/udp.c (ffffffff81c1c012)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81c22f84)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f1d2)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a36c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81c5c1b7)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c60870)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff815e90e0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff815ef03f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff815f5405)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81bfcb46)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff81c18e24)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff81c47581)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/tso.c (ffffffff81c4eebd)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff81c5c7b5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81c65764)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
```
```
In net/core/selftests.c (ffffffff81c6ebb1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81c71958)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/bpf/test_run.c (ffffffff81cb5476)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81ccba30)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81ccc648)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81cd110a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
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
Location: include/linux/ip.h:19
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
In net/ipv4/ip_fragment.c (ffffffff81cd6d05)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81cd7266)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81cd76f5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff81cdd4c4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81cf062a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d0f2)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81d14795)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff81d15f61)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81d1ee5b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f6f5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff81d21cbb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81f0897f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81d2d8b5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81d30acf)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81d441a0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d46135)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81d58ad8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81d5aa58)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d607a0)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81d6156e)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81d61855)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d67405)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d9ba)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81d7672a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81d784ea)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (ffffffff81db881b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81dbfdf1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc5ef)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81de9a3b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81dfdf58)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e02d84)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff816989c0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff8169f31f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff816a5ee5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81daba76)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff81dc9dec)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff81dfbae1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/tso.c (ffffffff81e03f6d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff81e12ea5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81e1c421)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
```
```
In net/core/selftests.c (ffffffff81e268f1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81e29a48)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/bpf/test_run.c (ffffffff81e7393a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b880)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81e8c568)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81e9138a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
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
Location: include/linux/ip.h:19
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
In net/ipv4/ip_fragment.c (ffffffff81e97295)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81e97887)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81e97d75)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff81e9df88)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81eb398e)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2b6c)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81eda8c5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff81edcdea)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81ee5f6b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ee68d5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff81ee910b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81eecda3)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81ef57b5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81ef8bdf)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81f0d66f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f515)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f22ede)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81f24ec8)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f2af60)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f2be9e)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81f2c1d5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f32455)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38faa)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42e98)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44e2b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (ffffffff81f88823)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81f90551)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d706)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd17b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81fd2b18)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd7ca4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff816d0e69)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff816d8106)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff816de8c5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81e1b57a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff81e3a975)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff81e6c9e1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81e7675a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff81e867d4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81e907e1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
```
```
In net/core/selftests.c (ffffffff81e9be91)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81e9f089)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/bpf/test_run.c (ffffffff81ecf668)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81ee98ca)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81eea768)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81eefb0a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
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
Location: include/linux/ip.h:19
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
In net/ipv4/ip_fragment.c (ffffffff81ef5ac5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81ef60c4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81ef65d5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff81efc752)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81f120b7)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31853)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81f399a5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff81f3c03a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81f4576b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81f46115)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff81f48ad7)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81f4c799)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81f55165)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81f5864f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81f6d2d3)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f205)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f82a1e)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81f84a61)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8ac30)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81f8bb3e)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81f8be8c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f93605)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:decode_session4
```
```
In net/xfrm/xfrm_state.c (ffffffff81f98833)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa2672)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa4619)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (ffffffff81fe914a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81ff0db1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe18a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff8201df2b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
```
```
In net/netlabel/netlabel_kapi.c (ffffffff8204e768)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82053994)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff8170d489)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff81714393)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff8171b495)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81ed8b3a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff81ef8cfa)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (ffffffff81f2c2bb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81f3671d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff81f487e1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81f52bb1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:perf_trace_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_skb
```
```
In net/core/selftests.c (ffffffff81f5e5f1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81f617f9)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/bpf/test_run.c (ffffffff81f92fb8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nf_queue.c (ffffffff81fad5eb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/netfilter/utils.c (ffffffff81fae518)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81fb3c5a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_bug
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
Location: include/linux/ip.h:19
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
In net/ipv4/ip_fragment.c (ffffffff81fb9a75)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81fba054)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81fba565)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff81fc0692)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81fcf763)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7a4e)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffa95)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff8200215b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8200b8bb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp4_csum_init
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8200c255)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
```
```
In net/ipv4/arp.c (ffffffff8200ec34)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff820128a9)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff8201b3d5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff8201eb0f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff82033a27)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035935)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8204909e)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
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
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff8204b2c4)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82052340)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8205343e)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff8205378c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/ipv4/tcp_ao.c (ffffffff820589b7)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_calc_key_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff82065ba3)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f9c5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff82071957)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (ffffffff820b6c52)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff820be991)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ccfa7)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff820ecf0b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
```
```
In net/netlabel/netlabel_kapi.c (ffffffff82120de8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82126184)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffff80001056c5b4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffff800010571948)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffff800010577774)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e602c)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/core/skbuff.c (ffff800010bb8dd8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffff800010bd0c20)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/core/tso.c (ffff800010c04a60)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffff800010c116fc)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffff800010c1f36c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffff800010c55f0c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffff800010c56cec)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffff800010c5aa6c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
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
In net/ipv4/ip_input.c (ffff800010c5ed70)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffff800010c5fdb0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffff800010c602d4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffff800010c60db4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffff800010c659f8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e8f8)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffff800010c95168)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffff800010c9649c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffff800010c9f6f4)
Location: include/linux/ip.h:19
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
In net/ipv4/udp_offload.c (ffff800010ca00b8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffff800010ca1c20)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffff800010ca47b0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffff800010cab7c4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffff800010cae778)
Location: include/linux/ip.h:19
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
In net/ipv4/fib_frontend.c (ffff800010cb4c20)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffff800010cc00e0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc2504)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffff800010cd0068)
Location: include/linux/ip.h:19
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffff800010cd20ac)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd6f00)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7788)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7f74)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdb604)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffff800010ce3408)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffff800010cea404)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010ceba5c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (ffff800010d26254)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffff800010d2c2dc)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38560)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffff800010d50d90)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffff800010d6432c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d69440)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (c071fe20)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (c0724c08)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (c072a5a4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac9378)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/core/skbuff.c (c0cd580c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (c0ceb854)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/core/tso.c (c0d1decc)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (c0d2946c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (c0d36f20)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (c0d65920)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (c0d663f8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (c0d67ee0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_multipath_l3_keys
  - net/ipv4/route.c:ip_mc_validate_source
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
In net/ipv4/ip_input.c (c0d6d918)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (c0d6fb84)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (c0d7077c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (c0d7565c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (c0d9dee0)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv4/tcp_offload.c (c0da38b4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (c0da5748)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0daca1c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (c0dad01c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (c0daea60)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (c0db1620)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (c0db8694)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (c0dbcac8)
Location: include/linux/ip.h:19
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
In net/ipv4/fib_frontend.c (c0dc05d4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (c0dcc5d0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (c0dcddf0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (c0dda610)
Location: include/linux/ip.h:19
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (c0ddbf3c)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (c0de0c10)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (c0de12b0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (c0de1a28)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (c0de6000)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (c0dec9f0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (c0df253c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_output.c (c0df3ad8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (c0e2a64c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (c0e30174)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (c0e3b874)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (c0e518ec)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (c0e62f40)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (c0e67b34)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (c0000000006d0878)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (c0000000006d8774)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (c0000000006e0de8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (c000000000c9124c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (c000000000caec40)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/core/tso.c (c000000000ceea08)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (c000000000cfe47c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (c000000000d11228)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (c000000000d5671c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (c000000000d57974)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (c000000000d5c674)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
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
In net/ipv4/ip_input.c (c000000000d60c54)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (c000000000d631d8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (c000000000d6402c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (c000000000d6a158)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d320)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv4/tcp_offload.c (c000000000da60f0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (c000000000da7da8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c000000000db21c8)
Location: include/linux/ip.h:19
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
In net/ipv4/udp_offload.c (c000000000db2b50)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (c000000000db4ee8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (c000000000db851c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (c000000000dc20f8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (c000000000dc6b80)
Location: include/linux/ip.h:19
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
In net/ipv4/fib_frontend.c (c000000000dcbe70)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (c000000000ddb4bc)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dddc30)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (c000000000dee30c)
Location: include/linux/ip.h:19
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (c000000000df0484)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (c000000000df6c34)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (c000000000df75fc)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (c000000000df80b0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (c000000000e00710)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (c000000000e06b20)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (c000000000e0dfb4)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_output.c (c000000000e0f940)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (c000000000e53fc0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (c000000000e5db6c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6bd54)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (c000000000e88c0c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (c000000000e9fc50)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea6330)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffe0003c106a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffe0003c5ab8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffe0003c9cbe)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffe000748478)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffe00075b2ac)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/core/tso.c (ffffffe000783614)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffe00078d920)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffe000798acc)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffe0007c0258)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffe0007c0c42)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffe0007c3e5c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
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
In net/ipv4/ip_input.c (ffffffe0007c6bd8)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffe0007c8562)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffe0007c8fac)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffe0007cd11c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eebfe)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4390)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffe0007f56a6)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffe0007fc232)
Location: include/linux/ip.h:19
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
In net/ipv4/udp_offload.c (ffffffe0007fc80c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffe0007fec3a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffe000800696)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffe00080644a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffe000809af4)
Location: include/linux/ip.h:19
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
In net/ipv4/fib_frontend.c (ffffffe00080c7c4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffe000816b64)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe00081796a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffe000822020)
Location: include/linux/ip.h:19
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffe00082344c)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008277ea)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffe000827e8c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffe000828514)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082cf0c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffe000831c3c)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffe000838040)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe00083936e)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (ffffffe0008654d4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffe00086c5a6)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008756c2)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffe0008890b6)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffffffe0008983b4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089c4bc)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff814740a5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814787cb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff8147d885)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818be604)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff818d2be1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/core/tso.c (ffffffff81901151)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff8190af3b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff8191859b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff819464fe)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff8194701a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff8194a526)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
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
In net/ipv4/ip_input.c (ffffffff8194e67c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff8194f438)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff8194fa8a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81950605)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff819550d0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197bb19)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81980fa5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff819824a3)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81989d64)
Location: include/linux/ip.h:19
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
In net/ipv4/udp_offload.c (ffffffff8198a375)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffff8198bf23)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff8198f262)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff819958d5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81998d54)
Location: include/linux/ip.h:19
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
In net/ipv4/fib_frontend.c (ffffffff8199c584)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff819a6f6c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8f8a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819b43a5)
Location: include/linux/ip.h:19
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff819b5a27)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819ba524)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff819baba5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb32d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffff819becf3)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff819c54b3)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb017)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc495)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (ffffffff819fe472)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81a059f3)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f2df)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a24378)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81a349eb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a38e77)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff81464ac5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff814691eb)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff8146e2a5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/vxlan.c (ffffffff81773c34)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/skbuff.c (ffffffff81878544)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff8188ca71)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/core/tso.c (ffffffff818baf81)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff818c4cd6)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff818d234b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff818fffee)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff81900b0a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff81904016)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
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
In net/ipv4/ip_input.c (ffffffff8190816c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff81908f28)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff8190957a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff8190a0f5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff8190ebc0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819355d9)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff8193aa65)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff8193bf63)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81943824)
Location: include/linux/ip.h:19
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
In net/ipv4/udp_offload.c (ffffffff81943e35)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffff819459e3)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81948d22)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8194f395)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81952814)
Location: include/linux/ip.h:19
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
In net/ipv4/fib_frontend.c (ffffffff81956044)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81960a2c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962a4a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967bf5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/ipv4/ipmr.c (ffffffff819709d5)
Location: include/linux/ip.h:19
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/udp_tunnel.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81972817)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81977314)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977995)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197811d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197bae3)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff819822a3)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81987e07)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81989285)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (ffffffff819bb232)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff819c27b3)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc09f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819e1138)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffffffff819f160b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f5a97)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff81470145)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff8147486b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff81479925)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8190f604)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff81923be1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/core/tso.c (ffffffff81952181)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff8195bf6b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff8196972b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff8199768e)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff819981aa)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a4285)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/netfilter/nf_conntrack_proto_icmp.c (ffffffff819a7b19)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_icmpv4_error
```
```
In net/netfilter/nf_conntrack_seqadj.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv4/route.c (ffffffff819b4cf6)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
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
In net/ipv4/ip_input.c (ffffffff819b8e4c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9c08)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819ba25a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff819badd5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff819bf8a0)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e62e9)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819eb775)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff819ecc73)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819f4534)
Location: include/linux/ip.h:19
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
In net/ipv4/udp_offload.c (ffffffff819f4b45)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffff819f6733)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff819f9b02)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81a00175)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81a035f4)
Location: include/linux/ip.h:19
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
In net/ipv4/fib_frontend.c (ffffffff81a06e24)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81a1180c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1382a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a1ec45)
Location: include/linux/ip.h:19
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81a202c7)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/netfilter/nf_defrag_ipv4.c (ffffffff81a20bd9)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a24fa4)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a25625)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25dad)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a29773)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2ff33)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35a97)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36f15)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (ffffffff81a68ef2)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81a70473)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a79d5f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a8edf8)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81aa089b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa4d27)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
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
In security/selinux/netlabel.c (ffffffff814879b5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
```
In security/smack/smack_lsm.c (ffffffff8148c1e2)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
```
```
In security/lsm_audit.c (ffffffff814913d5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81930734)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/dev.c (ffffffff81945051)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
```
In net/core/filter.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/core/tso.c (ffffffff81973bc1)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff8197e34b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff8198bb0b)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/netfilter/nf_queue.c (ffffffff819ba36e)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/utils.c (ffffffff819bae8a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (ffffffff819be436)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mc_validate_source
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
In net/ipv4/ip_input.c (ffffffff819c26fe)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
```
In net/ipv4/ip_fragment.c (ffffffff819c3648)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819c3b4a)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff819c46d5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:ip_forward_options
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_echo
```
```
In net/ipv4/ip_output.c (ffffffff819c921f)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_frag_next
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819effa9)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5625)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
```
In net/ipv4/raw.c (ffffffff819f6b63)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819fe6f4)
Location: include/linux/ip.h:19
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
In net/ipv4/udp_offload.c (ffffffff819fed15)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
```
```
In net/ipv4/arp.c (ffffffff81a0094d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81a03df2)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81a0a1c5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/igmp.c (ffffffff81a0db44)
Location: include/linux/ip.h:19
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
In net/ipv4/fib_frontend.c (ffffffff81a114d4)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
```
In net/ipv4/ping.c (ffffffff81a1c17c)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e1fa)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a2a101)
Location: include/linux/ip.h:19
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
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/ipv4/syncookies.c (ffffffff81a2b7c7)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a30414)
Location: include/linux/ip.h:19
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
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_extract_header
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30aa5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a3125d)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a34d03)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_decode_session
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3b8b3)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41407)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a428a5)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/udp.c (ffffffff81a754dd)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/icmp.c (ffffffff81a7ca93)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86552)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/ip.h:19
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bb68)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
```
In net/netlabel/netlabel_kapi.c (ffffffff81aacb44)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_skbuff_setattr
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab10a3)
Location: include/linux/ip.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_getattr
```
</details>
</li>
</ul>

## Differences
