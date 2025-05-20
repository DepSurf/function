# Function: <code>skb_transport_header</code>

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
In security/lsm_audit.c (ffffffff8136622e)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:1996
Inline: True
```
```
In net/core/dev.c (ffffffff8171ce63)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff817340b5)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_start
```
```
In net/core/netpoll.c (ffffffff817393e3)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (0)
Location: include/linux/skbuff.h:1996
Inline: True
```
```
In net/ipv4/route.c (ffffffff817549ec)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/skbuff.h:1996
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175f6a3)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/ip_sockglue.c (ffffffff8175fb57)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp.c (ffffffff81766c67)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff8176b627)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81774ce1)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177a9e6)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177f7a2)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/skbuff.h:1996
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81783308)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/raw.c (ffffffff817858a3)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff81786561)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/udp_offload.c (ffffffff8178b059)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8178dcca)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_err
```
```
In net/ipv4/igmp.c (ffffffff817954bc)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/ping.c (ffffffff817a2ed1)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_rcv
```
```
In net/ipv4/gre_offload.c (ffffffff817a514c)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff817a843d)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff817ab419)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_input.c (ffffffff817b0004)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/skbuff.h:1996
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:1996
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/skbuff.h:1996
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d7852)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff817de9a0)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff817e1b1e)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:1996
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff817e764e)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff817ea1d4)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_report
```
```
In net/ipv6/reassembly.c (ffffffff817edd63)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817eedd0)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_sequence
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f2bcb)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/datagram.c (ffffffff817f4a6d)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/ip6mr.c (ffffffff817f858d)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff817ff2c8)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/ip6_checksum.c (ffffffff818000d4)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (0)
Location: include/linux/skbuff.h:1996
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (ffffffff8180129b)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/udp_offload.c (ffffffff818016cc)
Location: include/linux/skbuff.h:1996
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/mcast_snoop.c (ffffffff8180282d)
Location: include/linux/skbuff.h:1996
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
In security/lsm_audit.c (ffffffff8139c30e)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8176bf6c)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff817855a7)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__skb_csum_offload_chk
```
```
In net/core/tso.c (ffffffff8179fd05)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff817a569b)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff817a822c)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff817c0b6c)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff817cb943)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cdc95)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff817d314f)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff817dc8c4)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ec048)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec781)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817f0089)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0736)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff817f2d03)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff817f7f0d)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff817f86a3)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff817fcaa4)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81805884)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81811da9)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffff81812c0f)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81815b1d)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff81818f09)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181cf34)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff818287df)
Location: include/linux/skbuff.h:2126
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81835262)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff818357e3)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/route.c (ffffffff81845f99)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff8184facf)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff8184ff8e)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81854a13)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81856f8c)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81858eef)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8185ce42)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860bf0)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_sequence
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffff81862b20)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff818642c8)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81866a34)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81867d6d)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff8186ec52)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/ip6_checksum.c (ffffffff81871791)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff8187266c)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872adb)
Location: include/linux/skbuff.h:2126
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81873ade)
Location: include/linux/skbuff.h:2126
Inline: True
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
In security/lsm_audit.c (ffffffff813b2ebe)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8179914c)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff817b2bb7)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (0)
Location: include/linux/skbuff.h:2143
Inline: True
```
```
In net/core/tso.c (ffffffff817ce6d5)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff817d410b)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff817d6d7a)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff817f004c)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff817fb5a5)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fd9f5)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81804a3e)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff8180c9c2)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c9d0)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181d071)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81820aa7)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff818214a6)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81823ac4)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81828dad)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81829553)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8182da04)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81836cd4)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff818432b9)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffff81844116)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818472cd)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff8184a769)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e7f4)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a1bf)
Location: include/linux/skbuff.h:2143
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81866da0)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81867313)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/route.c (ffffffff81877cf9)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff818819ef)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81881d8e)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81886745)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81888d8c)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff8188accf)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8188ed80)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892bbc)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_sequence
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffff81895130)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff8189697c)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81899134)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8189abcd)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff818a1ba2)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a4e32)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5cf1)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6c6c)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a70fb)
Location: include/linux/skbuff.h:2143
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a815e)
Location: include/linux/skbuff.h:2143
Inline: True
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
In security/lsm_audit.c (ffffffff813c988e)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff817b7722)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff817d03c7)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff817eaccd)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff817edb85)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff817f3450)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff817f6dea)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff818100fc)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff8181b977)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181de35)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81824d76)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff8182cbf1)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183d1c5)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d88d)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818410ba)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81842186)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81844652)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8184a08d)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8184a56e)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8184eea9)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81858476)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81864b09)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffff81865980)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81868cbd)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff8186e10d)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff818722c4)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/skbuff.h:2182
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e02f)
Location: include/linux/skbuff.h:2182
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8188ac37)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff8188ba93)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/route.c (ffffffff8189ce89)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff818a7b07)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff818a856e)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff818accbd)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff818af410)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff818b1a10)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff818b5229)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b91a9)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffff818bb4b0)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff818bcefa)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff818bf355)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff818c1505)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/skbuff.h:2182
Inline: True
```
```
In net/ipv6/syncookies.c (ffffffff818c8169)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb872)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc751)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd69b)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdb6b)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce99e)
Location: include/linux/skbuff.h:2182
Inline: True
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
In security/lsm_audit.c (ffffffff813efd1e)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8182fde2)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81849d53)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8186777d)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff81869dc5)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff8186e840)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff818733cd)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff8188f7cc)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff8189a8b0)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189cd45)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff818a36e6)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff818abaeb)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc9b0)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bcf9d)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0822)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1a66)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff818c3f8e)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff818c9c48)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff818ca209)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff818cec29)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff818d8346)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff818e4c69)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffff818e5acc)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff818e91fd)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff818eea9d)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2ca4)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/skbuff.h:2269
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff818fef5f)
Location: include/linux/skbuff.h:2269
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8190be2e)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff8190cd73)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/route.c (ffffffff8191c829)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff8192a5b7)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff8192b01e)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff8192f645)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81932120)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81933d99)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81937f9f)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193c0f5)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffff8193e4cf)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff8194001a)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff819424af)
Location: include/linux/skbuff.h:2269
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81944855)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/skbuff.h:2269
Inline: True
```
```
In net/ipv6/syncookies.c (ffffffff8194b719)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/skbuff.h:2269
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950612)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffff81951501)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff8195248d)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff8195296b)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff8195384e)
Location: include/linux/skbuff.h:2269
Inline: True
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
In security/lsm_audit.c (ffffffff814212c2)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8187a462)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81893f51)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818b57e2)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff818b9a9c)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff818bf9d5)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff818c4b47)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff818e356c)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff818eed80)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f1221)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff818f8a42)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81900680)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819124ef)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912dfe)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819163e7)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81917702)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81919c7e)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8191fcf3)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81920da1)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81925042)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff8192de3c)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff8193b54f)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffff8193c3c4)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8193fcff)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff819453b8)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff819495dd)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81955a24)
Location: include/linux/skbuff.h:2280
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81962eda)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81964187)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/route.c (ffffffff81974f5b)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/ndisc.c (ffffffff8198282d)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81985310)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819882ed)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff8198ac70)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff8198c92a)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81991161)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819954e6)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffff81997405)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81998e7b)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff8199b2dc)
Location: include/linux/skbuff.h:2280
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8199d574)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff819a49c9)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7798)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9b3e)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aaa9e)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff819aba10)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819abf25)
Location: include/linux/skbuff.h:2280
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad270)
Location: include/linux/skbuff.h:2280
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
In security/lsm_audit.c (ffffffff8143d962)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff8189b072)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff818b493e)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818dc3e6)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff818e085c)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff818e87f5)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff818edbb7)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff8191041c)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff8191c56f)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191ed81)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81926772)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff8192e7d8)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940cc9)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819415be)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944b87)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81945e3f)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819484f7)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8194e963)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8194f1c0)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81953e52)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff8195d6fd)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff8196b23f)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffff8196c0bc)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8196f599)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff81975748)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b2a7)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a4fe)
Location: include/linux/skbuff.h:2358
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81997ec3)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ip6_input.c (ffffffff81999a47)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819aab9b)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/ndisc.c (ffffffff819b8eca)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bba90)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819becfb)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff819c1534)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff819c31aa)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c78a3)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbdcb)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffff819cdcdf)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff819cf971)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff819d1c16)
Location: include/linux/skbuff.h:2358
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d40d4)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff819db4d9)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de305)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e065e)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e158e)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff819e25a7)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2b02)
Location: include/linux/skbuff.h:2358
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3c17)
Location: include/linux/skbuff.h:2358
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
In security/lsm_audit.c (ffffffff8146b520)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818e5752)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81901293)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff819294e6)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff8192eeec)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff81938007)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff8193e4ed)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff81972e6c)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff8197e895)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff8198168d)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81987632)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81991d91)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a52a3)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5bb8)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a91ed)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa475)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819acf69)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819b3144)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819b39bd)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff819b876d)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff819c2371)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff819d1f0e)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffff819d2e0f)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819d8cd9)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff819df268)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e47d8)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff819f484e)
Location: include/linux/skbuff.h:2446
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6245)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a01444)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff81a05977)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a17e6d)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff81a2793f)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a2a6d0)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a2dc02)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a30323)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81a31fea)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a360d0)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a8be)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c8ef)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a3e688)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a409ce)
Location: include/linux/skbuff.h:2446
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a42f81)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81a4a149)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4ce6c)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f2c1)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a50351)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a5126a)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a51848)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a528bd)
Location: include/linux/skbuff.h:2446
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In security/lsm_audit.c (ffffffff81485300)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819178a2)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff819335c3)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8195bbc2)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff8196115f)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff8196aec7)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff8197137d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff819a97dc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff819b5235)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b7ecd)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff819bddf2)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff819c89a5)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbf99)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc978)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819dfd94)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1145)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819e3c39)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819e9ec4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819ea6ed)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff819ef46d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff819f8f11)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81a08a7e)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffff81a0997d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a0fa3e)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff81a162f8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b7e8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b4fe)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2cec5)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a38024)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c4f6)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a4eacd)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff81a5e39f)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a61220)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a6476d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a66e73)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81a68b3a)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a6cbf0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a71461)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffff81a7356f)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a752f8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a7764e)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a79ae1)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81a80d09)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83a3c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a85f51)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a86f71)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87e8a)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a88448)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a8949d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In security/lsm_audit.c (ffffffff814db4a0)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff8188adc7)
Location: include/linux/skbuff.h:2483
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ea5e5)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/dev.c (ffffffff81a00d5a)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81a2edb5)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff81a34672)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff81a3ec2b)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81a452d5)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff81a92c0e)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81a9f489)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa27e6)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81ab3ed2)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_measure_rcv_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac90dc)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9a48)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acd0dc)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81ace725)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81ad093d)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_err
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ad7a9a)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81ad7f7e)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81add3bd)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81ae6cca)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81af82bb)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffff81afa0ed)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b032fe)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff81b07326)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c880)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e235)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1edcd)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21ac6)
Location: include/linux/skbuff.h:2483
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b23125)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81b30c0c)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff81b31b96)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81b463eb)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81b5717f)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b5784c)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err_encap
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b5b8da)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b5f73b)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81b61108)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b6629b)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6ad6a)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d9cb)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:seg6_update_csum
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b6f52d)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81b7197e)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b744aa)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78c20)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81b7b98c)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e802)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80f77)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b82205)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81b8334f)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83914)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84915)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
```
In net/packet/af_packet.c (ffffffff81b86d17)
Location: include/linux/skbuff.h:2483
Inline: True
```
```
In net/mptcp/options.c (ffffffff81bb0ea5)
Location: include/linux/skbuff.h:2483
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
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
In security/lsm_audit.c (ffffffff814f8930)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff81898ee7)
Location: include/linux/skbuff.h:2504
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ea332)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/dev.c (ffffffff81a0116a)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81a308cb)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff81a36a49)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff81a419cb)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81a494ea)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff81a9caae)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81aa93c9)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacab6)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81abe831)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_measure_rcv_mss
```
```
In net/ipv4/tcp_output.c (ffffffff81ac75a3)
Location: include/linux/skbuff.h:2504
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad507c)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5998)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad90ec)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81ada75a)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81adc95b)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_err
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ae40ea)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81ae47e9)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81aea10d)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81af3b9a)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81b0511b)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06d02)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/gre_offload.c (ffffffff81b077cf)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81b1145e)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff81b156f4)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1abb0)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2cb05)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d67d)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
  - net/xfrm/xfrm_output.c:xfrm4_transport_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30496)
Location: include/linux/skbuff.h:2504
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b31b15)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f834)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff81b40796)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81b54f2b)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81b657ef)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b65d5c)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err_encap
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b6a126)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b6dedb)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81b6f888)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b74a1b)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b77032)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c47b)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:seg6_update_csum
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b7e05d)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81b80622)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b8321d)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87ba0)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81b8a9cc)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d812)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90797)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91902)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81b929fe)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b92fd4)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b94275)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
```
In net/packet/af_packet.c (ffffffff81b967f7)
Location: include/linux/skbuff.h:2504
Inline: True
```
```
In net/mptcp/options.c (ffffffff81bc4bf5)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
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
In security/lsm_audit.c (ffffffff814ff6a4)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff8187c5e7)
Location: include/linux/skbuff.h:2520
Inline: True
```
```
In net/core/skbuff.c (ffffffff819d08f2)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/dev.c (ffffffff819e79cc)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81a13c9a)
Location: include/linux/skbuff.h:2520
Inline: True
```
```
In net/core/tso.c (ffffffff81a1dbc4)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff81a2648b)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81a2e44c)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81a36381)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81a87b6a)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81a94592)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a97d08)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81a9e636)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81aaab94)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81ab25c2)
Location: include/linux/skbuff.h:2520
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac00fe)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac09f7)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3f4c)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac57da)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81ac799c)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81acf2da)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81acfa0d)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81ad5876)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81adf34d)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81af097c)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af243b)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/gre_offload.c (ffffffff81af2fa5)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81aff08e)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff81b03507)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0886d)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a745)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c101)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e309)
Location: include/linux/skbuff.h:2520
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b1f845)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d6d8)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e026)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81b429c0)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81b53a9f)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b53dff)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b58456)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b5c25a)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81b5dbe1)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81b6353f)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b65b52)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81b6af8b)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b6cc61)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f244)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81b71e97)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b7685d)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81b79839)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c6c2)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7f9cd)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80b50)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81b56)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b82124)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b83375)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81b85797)
Location: include/linux/skbuff.h:2520
Inline: True
```
```
In net/mptcp/options.c (ffffffff81bb5265)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
```
```
In net/mptcp/syncookies.c (ffffffff81bbcc95)
Location: include/linux/skbuff.h:2520
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In security/lsm_audit.c (ffffffff8155a714)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff8190db8c)
Location: include/linux/skbuff.h:2549
Inline: True
```
```
In net/core/skbuff.c (ffffffff81a805e2)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/dev.c (ffffffff81a980ec)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81ac575a)
Location: include/linux/skbuff.h:2549
Inline: True
```
```
In net/core/tso.c (ffffffff81ad1664)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff81adb1f4)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81ae3a2c)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81aec05c)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81b4209a)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81b4fa12)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b53198)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81b5a3f6)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81b66f84)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f462)
Location: include/linux/skbuff.h:2549
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7dd6e)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e3b7)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b825dc)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81b83fea)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81b861f9)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81b8dcfa)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e42d)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81b94736)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81b9e82d)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81bb07ec)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb294b)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/gre_offload.c (ffffffff81bb34b5)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81bc226e)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff81bc5797)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb76d)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81bded65)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0a8d)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2df9)
Location: include/linux/skbuff.h:2549
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81be4485)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81bf38b7)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4306)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81c08120)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81c1afdf)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81c1d2af)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81c1f7e6)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81c239c1)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81c25091)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81c2afff)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2c583)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81c32deb)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81c34b1b)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81c37304)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c347)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c412dd)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81c444e3)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47696)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b26d)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bf24)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4cb70)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dbab)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e1d4)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f445)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81c51b0c)
Location: include/linux/skbuff.h:2549
Inline: True
```
```
In net/mptcp/options.c (ffffffff81c83e45)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
```
```
In net/mptcp/syncookies.c (ffffffff81c8caf5)
Location: include/linux/skbuff.h:2549
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In security/lsm_audit.c (ffffffff815f5465)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff81a63587)
Location: include/linux/skbuff.h:2917
Inline: True
```
```
In net/core/skbuff.c (ffffffff81bf4cc2)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/dev.c (ffffffff81c0fd9c)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81c4128f)
Location: include/linux/skbuff.h:2917
Inline: True
```
```
In net/core/tso.c (ffffffff81c4ef69)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff81c5c707)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81c67207)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81c6e9fb)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81cdd491)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdf88a)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81ce7c73)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81cf65f5)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81cfeb12)
Location: include/linux/skbuff.h:2917
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0dd7f)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e335)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d12b0f)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81d147a9)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81d16b60)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81d1ee2a)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f661)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81d25ff6)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81d30b92)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81d43d9b)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d46127)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/gre_offload.c (ffffffff81d46cd8)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81d52b7d)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff81d5a9a9)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d6122b)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81d765b2)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_output.c (ffffffff81d777af)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79f99)
Location: include/linux/skbuff.h:2917
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81d7b936)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c48e)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d017)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81da2eae)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81db75fc)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81db9909)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81dbc401)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81dc08da)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81dc2392)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81dc82af)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc9845)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81dd05cb)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81dd24d4)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81dd4eb2)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81dda6ef)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddfa6b)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81de34b3)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6a69)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deabb6)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81debeb6)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81decfc2)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee27a)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deea92)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defe75)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81df3af7)
Location: include/linux/skbuff.h:2917
Inline: True
```
```
In net/mptcp/options.c (ffffffff81e29fe5)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
```
```
In net/mptcp/syncookies.c (ffffffff81e361a5)
Location: include/linux/skbuff.h:2917
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
```
```
In net/mctp/route.c (ffffffff81e39064)
Location: include/linux/skbuff.h:2917
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
In security/lsm_audit.c (ffffffff816a5f3f)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff81beebe0)
Location: include/linux/skbuff.h:2809
Inline: True
```
```
In net/core/skbuff.c (ffffffff81da2ce2)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/dev.c (ffffffff81dbf7dc)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81df69ef)
Location: include/linux/skbuff.h:2809
Inline: True
```
```
In net/core/tso.c (ffffffff81e04019)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff81e12df7)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81e1e323)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81e2672b)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81e9df50)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9e2da)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81eab559)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81ebb005)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3a42)
Location: include/linux/skbuff.h:2809
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed372b)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3de5)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed895e)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81eda8d9)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81edd31d)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ee5f3a)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6831)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81eed826)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81ef8ca2)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81f0cdfb)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f507)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/gre_offload.c (ffffffff81f10528)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f1cecd)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff81f24e19)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2bb2b)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42d14)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_output.c (ffffffff81f4403f)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46dd9)
Location: include/linux/skbuff.h:2809
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81f489d6)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a44e)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b415)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81f722be)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81f872ec)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81f89999)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81f8d6c6)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81f91057)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81f93092)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81f9903f)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9a7c5)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff81fa197b)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81fa3954)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81fa65b8)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff81fac40f)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1d5b)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81fb5b33)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9891)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe776)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfb16)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc0dc2)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc27d9)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2ad2)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3f95)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff81fc89b0)
Location: include/linux/skbuff.h:2809
Inline: True
```
```
In net/mptcp/options.c (ffffffff82002105)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
```
```
In net/mptcp/syncookies.c (ffffffff8200f175)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
```
```
In net/mctp/route.c (ffffffff82012384)
Location: include/linux/skbuff.h:2809
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
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
In security/lsm_audit.c (ffffffff816de91f)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff81c4792f)
Location: include/linux/skbuff.h:2863
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c4e1cf)
Location: include/linux/skbuff.h:2863
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e1d0b5)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/dev.c (ffffffff81e2f484)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
```
```
In net/core/filter.c (ffffffff81e6749c)
Location: include/linux/skbuff.h:2863
Inline: True
```
```
In net/core/tso.c (ffffffff81e768b8)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/gso.c (ffffffff81e7d602)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_validate_mac_len
  - net/core/gso.c:skb_gso_validate_network_len
  - net/core/gso.c:skb_gso_transport_seglen
  - net/core/gso.c:skb_gso_transport_seglen
```
```
In net/core/netpoll.c (ffffffff81e86720)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81e95666)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81e9bccc)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81efc71a)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efcada)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81f09c79)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81f19496)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81f21c82)
Location: include/linux/skbuff.h:2863
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f32437)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32dd9)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f37a6e)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81f399b9)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81f3c56b)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81f4573a)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff81f46071)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81f4d1e6)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81f58712)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81f6ca6b)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f1f7)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/gre_offload.c (ffffffff81f70215)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81f7c9ad)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff81f849a9)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b56b)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa24fa)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3901)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6790)
Location: include/linux/skbuff.h:2863
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81fa8846)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81fba105)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb1e7)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81fd23ae)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff81fe7626)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81fe9249)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81fedbf8)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81ff1947)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81ff3691)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81ff9a0f)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffb325)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff820021ef)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff82004233)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff82006e02)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff8200cbaf)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012469)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/syncookies.c (ffffffff82016244)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019f21)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f616)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020aa6)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff82021d52)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff82023757)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023a62)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024fb5)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/packet/af_packet.c (ffffffff820292ef)
Location: include/linux/skbuff.h:2863
Inline: True
```
```
In net/mptcp/options.c (ffffffff8207e2c5)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
```
```
In net/mptcp/syncookies.c (ffffffff8208bd65)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
```
```
In net/mctp/route.c (ffffffff8208f174)
Location: include/linux/skbuff.h:2863
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
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
In security/lsm_audit.c (ffffffff8171b4ef)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/tun.c (ffffffff81cfd242)
Location: include/linux/skbuff.h:2870
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d04242)
Location: include/linux/skbuff.h:2870
Inline: True
```
```
In net/core/skbuff.c (ffffffff81eda7a5)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_checksum_setup_ip
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/dev.c (ffffffff81ef96ec)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81f2665c)
Location: include/linux/skbuff.h:2870
Inline: True
```
```
In net/core/tso.c (ffffffff81f3687b)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/gso.c (ffffffff81f3e582)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_validate_mac_len
  - net/core/gso.c:skb_gso_validate_network_len
  - net/core/gso.c:skb_gso_transport_seglen
  - net/core/gso.c:skb_gso_transport_seglen
```
```
In net/core/netpoll.c (ffffffff81f4872d)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff81f57bdd)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/core/selftests.c (ffffffff81f5e42c)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81fc065a)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc0aea)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81fcf451)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
```
```
In net/ipv4/tcp_input.c (ffffffff81fddeaf)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5c22)
Location: include/linux/skbuff.h:2870
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff8402)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8f29)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffdb3e)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffaa9)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff8200269a)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff8200b88a)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8200c1b1)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff820132f6)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff8201ebd2)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff820331bb)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035927)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
```
```
In net/ipv4/gre_offload.c (ffffffff82036945)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff820430ad)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff8204b222)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c75d)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052c72)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
```
```
In net/ipv4/tcp_ao.c (ffffffff82058dab)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_finish_connect
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_ao_syncookie
  - net/ipv4/tcp_ao.c:tcp_ao_prepare_reset
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_calc_key_skb
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f843)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
  - net/xfrm/xfrm_input.c:xfrm_parse_spi
```
```
In net/xfrm/xfrm_output.c (ffffffff82070c31)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/xfrm/xfrm_device.c (ffffffff82073a80)
Location: include/linux/skbuff.h:2870
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff82075b36)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_push_skb
```
```
In net/ipv6/ip6_output.c (ffffffff82087567)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff820885f7)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff8209f93e)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
```
```
In net/ipv6/ndisc.c (ffffffff820b5486)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff820b5d59)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff820bb808)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff820bf546)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff820c170e)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff820c767f)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8c05)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/exthdrs.c (ffffffff820d0fef)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff820d2ff3)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff820d5c62)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
```
In net/ipv6/ip6mr.c (ffffffff820dbb7f)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e0e82)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
```
```
In net/ipv6/syncookies.c (ffffffff820e534c)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8ef1)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee746)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efbd6)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f0e72)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2bc2)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f4295)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/ipv6/tcp_ao.c (ffffffff820f489a)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/ipv6/tcp_ao.c:tcp_v6_ao_calc_key_skb
```
```
In net/packet/af_packet.c (ffffffff820f8d42)
Location: include/linux/skbuff.h:2870
Inline: True
```
```
In net/mptcp/options.c (ffffffff821537b5)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
```
```
In net/mptcp/syncookies.c (ffffffff82162225)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
```
```
In net/mctp/route.c (ffffffff82165654)
Location: include/linux/skbuff.h:2870
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_do_fragment_route
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
In security/lsm_audit.c (ffff8000105777e0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109eb5ec)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
```
```
In net/core/skbuff.c (ffff800010bb0c44)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffff800010bd16c4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (0)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/core/tso.c (ffff800010c04a60)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffff800010c11528)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffff800010c19da8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffff800010c593e8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffff800010c659f8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffff800010c692e0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffff800010c6fa78)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffff800010c7a630)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8f244)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f8dc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c9393c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffff800010c95180)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffff800010c98608)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffff800010c9ec18)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffff800010ca02cc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffff800010ca51f4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffff800010cae6d4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffff800010cc1c9c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffff800010cc2c94)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffff800010ccca38)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffff800010cd1ffc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7a48)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9cc8)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010cebb20)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffff800010cf87e0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffff800010cfd7dc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffff800010d12840)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffff800010d20e24)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d26e88)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d2a5d8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffff800010d2cdcc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffff800010d2f134)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffff800010d358e4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39868)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffff800010d3c034)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffff800010d3d3a4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffff800010d40cb8)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d43de0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (ffff800010d4c574)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f738)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffff800010d52824)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffff800010d536bc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffff800010d54a40)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d54fd8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffff800010d562cc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In security/lsm_audit.c (c072a60c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acd8c8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
```
```
In net/core/skbuff.c (c0cce0b4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_mac_len
  - net/core/skbuff.c:skb_gso_validate_network_len
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (c0cec2f4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (c0d175d8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (c0d1de80)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (c0d293d8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (c0d2f5f8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (c0d68f3c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (c0d75670)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (c0d784d4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (c0d7ee98)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (c0d88090)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (c0d9e184)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (c0d9e99c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (c0da22b8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (c0da38c8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (c0da5ca4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0dac9f0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (c0dacfc0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (c0db1b18)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (c0dbc9ec)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (c0dcd434)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (c0dce508)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c0dd7038)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (c0ddbe90)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (c0de1550)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (c0df2754)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_output.c (c0df3878)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c0dffee8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (c0e04fd8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (c0e185f0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (c0e27a18)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c0e282cc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2e64c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c0e30bf4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (c0e32fa4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c0e37b7c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (c0e3c378)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (c0e3f24c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (c0e40f6c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (c0e436a8)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e45b84)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (c0e4d834)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (c0e50508)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (c0e52cec)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (c0e53f70)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (c0e5506c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (c0e55598)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (c0e568a8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In security/lsm_audit.c (c0000000006e0e58)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (c000000000c86e58)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (c000000000cafa60)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (c000000000ce53bc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (c000000000cee9cc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (c000000000cfe214)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (c000000000d06868)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (c000000000d5b0bc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (c000000000d6a16c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (c000000000d6de64)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (c000000000d765ac)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (c000000000d851c0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9dec8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e8f4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (c000000000da3de0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (c000000000da6104)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (c000000000da9c90)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c000000000db219c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (c000000000db3b28)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (c000000000db9000)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (c000000000dc6acc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (c000000000ddd230)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (c000000000ddebf4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (c000000000de7634)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (c000000000df03c0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (c000000000df799c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (c000000000e0d980)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/xfrm/xfrm_output.c (c000000000e0f574)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (c000000000e20838)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (c000000000e258c0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (c000000000e3ee84)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (c000000000e53364)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c000000000e56d00)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c000000000e5b7cc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c000000000e5e8d8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (c000000000e61ed0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c000000000e679ac)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6cf48)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (c000000000e6fb4c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (c000000000e721f4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (c000000000e75430)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e78930)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (c000000000e82c20)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86e34)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (c000000000e8af10)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (c000000000e8be50)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (c000000000e8d5c0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8dcd4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f46c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In security/lsm_audit.c (ffffffe0003c9d12)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffe000741df6)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffe00075bb4e)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffe00077fa2c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffe000783614)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffe00078d6e2)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffe00079110e)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffe0007c30c4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffe0007cd120)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf206)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffe0007d4d78)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffe0007de2b4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ef3d2)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efc04)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2fa4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4398)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffe0007f67f2)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffe0007fc216)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffe0007fc9d2)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffe000800b24)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffe000809a68)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:add_grhead
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffe0008172ee)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffe000818104)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffe00081e2b6)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffe0008233d8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffe0008280e6)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffe000837c84)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe0008393fc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffe000844536)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffe000847d36)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffe000858c62)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffe000864d5c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffe000867fc8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffe00086ae1e)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffe00086d006)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffe00086efce)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:add_grhead
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffe000872d9a)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876af8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffe000878a6a)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffe00087a30a)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffe00087c4ce)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe00087e964)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (ffffffe0008852f4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000888026)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a822)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b3ce)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c3bc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c848)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088db60)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In security/lsm_audit.c (ffffffff8147d8e0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff818b78a2)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff818d35c3)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818fbb92)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff8190112f)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff8190ae97)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff8191134d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff8194964c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff819550a5)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff81957d3d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff8195dc62)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81968815)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197be09)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c7e8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197fc04)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81980fb5)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81983aa9)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81989d34)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8198a55d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff8198f20d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81998cb1)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff819a881e)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffff819a971d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff819af469)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff819b5988)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff819bae78)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff819cab8e)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc555)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff819d76b4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff819dbb86)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819ee15d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff819fda2f)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a008b0)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a03dfd)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a06503)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81a081ca)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a0c280)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10af1)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffff81a12bff)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a14988)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a16cde)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a19171)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81a20399)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a230cc)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a255e1)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a26601)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a2751a)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27ad8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28b2d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In security/lsm_audit.c (ffffffff8146e300)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In drivers/net/vxlan.c (ffffffff81770636)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_err_lookup
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/skbuff.c (ffffffff818717f2)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff8188d453)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818b59c2)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff818baf5f)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff818c4c32)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff818cb10d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff8190313c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff8190eb95)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191182d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff81917752)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81922305)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819358c9)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819362a8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819396c4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff8193aa75)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff8193d569)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819437f4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff8194401d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81948ccd)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81952771)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff819622de)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffff819631dd)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff8196ba99)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/udp_tunnel.c (ffffffff819720d3)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp_tunnel.c:udp_tun_rx_dst
  - net/ipv4/udp_tunnel.c:udp_tun_rx_dst
  - net/ipv4/udp_tunnel.c:udp_tun_rx_dst
  - net/ipv4/udp_tunnel.c:udp_tunnel_xmit_skb
```
```
In net/ipv4/syncookies.c (ffffffff81972778)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977c68)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff8198797e)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81989345)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81994474)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff81998946)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819aaf1d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff819ba7ef)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bd670)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819c0bbd)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff819c32c3)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff819c4f8a)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c9040)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd8b1)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffff819cf9bf)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff819d1748)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff819d3a9e)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d5f31)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff819dd159)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfe8c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e23a1)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e33c1)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff819e42da)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e4898)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/ip6_udp_tunnel.c (ffffffff819e5a46)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_udp_tunnel.c:udp_tunnel6_xmit_skb
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5d1d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In security/lsm_audit.c (ffffffff81479980)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff819088a2)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff819245c3)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8194cbc2)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff8195215f)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff8195bec7)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff8196237d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff819b3e1c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff819bf875)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c250d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff819c8432)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff819d2fe5)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e65d9)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6fb8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819ea3d4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff819eb785)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819ee279)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819f4504)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819f4d2d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff819f9aad)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81a03551)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81a130be)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffff81a13fbd)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a19d09)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff81a20228)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a258f8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81a3560e)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36fd5)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a42134)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff81a46606)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a58bdd)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff81a684af)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a6b330)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a6e87d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a70f83)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81a72c4a)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a76d00)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b571)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d67f)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a7f408)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a8175e)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a83bf1)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81a8ae19)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8db4c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a90061)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a91263)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a921b1)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a930ca)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a93688)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a946dd)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In security/lsm_audit.c (ffffffff81491430)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv4_skb_to_auditdata
```
```
In net/core/skbuff.c (ffffffff81929952)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/core/dev.c (ffffffff81945a53)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8196e582)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
```
```
In net/core/tso.c (ffffffff81973b9f)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/core/netpoll.c (ffffffff8197e2a7)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/net-traces.c (ffffffff819845ed)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:trace_event_raw_event_net_dev_start_xmit
```
```
In net/ipv4/route.c (ffffffff819bd50c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff819c91f4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cbf0d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp.c (ffffffff819d1f82)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff819dcb86)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819f0299)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0c88)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f4212)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5635)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff819f82d9)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819fe6c4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/udp_offload.c (ffffffff819fef12)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/icmp.c (ffffffff81a03d9d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/igmp.c (ffffffff81a0daa1)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:add_grec
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81a1da8e)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e9ad)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/ipmr.c (ffffffff81a24b2e)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:pim_rcv
  - net/ipv4/ipmr.c:pim_rcv_v1
```
```
In net/ipv4/syncookies.c (ffffffff81a2b728)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30d88)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40f6e)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42965)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/ip6_output.c (ffffffff81a4ddc4)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
```
In net/ipv6/ip6_input.c (ffffffff81a52336)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a64dbd)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/ndisc.c (ffffffff81a74a9f)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a77940)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a7aea5)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a7d593)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (ffffffff81a7f2ca)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a83320)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87db1)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/exthdrs.c (ffffffff81a89ecf)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_parse_hopopts
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a8bcc8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_icmp_error
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e05e)
Location: include/linux/skbuff.h:2460
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a90511)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff81a97a79)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a84c)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d1c5)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e261)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f270)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f7d8)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa083d)
Location: include/linux/skbuff.h:2460
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
</details>
</li>
</ul>

## Differences
