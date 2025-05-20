# Function: <code>inet6_sk</code>

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
In net/core/sock.c (ffffffff817014d7)
Location: include/linux/ipv6.h:267
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761e45)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81768344)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff817760be)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81780044)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff817806cb)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
```
```
In net/ipv4/udp.c (ffffffff81786cb8)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff817a2d1e)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff817c2985)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/anycast.c (ffffffff817c3db6)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_close
```
```
In net/ipv6/ip6_output.c (ffffffff817c4586)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/route.c (ffffffff817d4950)
Location: include/linux/ipv6.h:267
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817dc13e)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff817de5d5)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_na
```
```
In net/ipv6/udp.c (ffffffff817e1c84)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff817e5166)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_icmp_error
```
```
In net/ipv6/icmp.c (ffffffff817e7a32)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/mcast.c (ffffffff817e984c)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ipv6_sock_mc_join
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ipv6_sock_mc_close
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817ef8f6)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ping.c (ffffffff817f25d8)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff817f4076)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f6266)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff817f7327)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd16d)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff817ff2b6)
Location: include/linux/ipv6.h:267
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/core/sock.c (ffffffff817685d7)
Location: include/linux/ipv6.h:288
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff817ce185)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff817d4c25)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff817e5030)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ed566)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff817edc7c)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff817f3cf8)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81810536)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff8182f9e5)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81831306)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff818355f1)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81841f00)
Location: include/linux/ipv6.h:288
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184ae1e)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff8184c4f5)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81850429)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81854109)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81856884)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8185809c)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860aaf)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81861335)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81864170)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81865b69)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff8186684b)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186ca9d)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff8186ec39)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff818702b4)
Location: include/linux/ipv6.h:288
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/core/sock.c (ffffffff81795627)
Location: include/linux/ipv6.h:306
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdeeb)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81804938)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff818154ba)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181de76)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff8181e5fc)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff81824ad8)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81841a36)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81861465)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81862d76)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81867121)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81873230)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187ccbe)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff8187e3c5)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81882239)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81885e19)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81888686)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8188a15c)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892a7e)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81893275)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81896820)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81898239)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81898f4b)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189f88d)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff818a1b89)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff818a3224)
Location: include/linux/ipv6.h:306
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (ffffffff817af180)
Location: include/linux/ipv6.h:315
Inline: True
```
```
In net/core/sock.c (ffffffff817b32a0)
Location: include/linux/ipv6.h:315
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e303)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81824c8a)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff818353cc)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183e5e2)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff8183ec6d)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff81845832)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81863186)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81885ba5)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81887546)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff8188b8a7)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81897c00)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a27be)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff818a4415)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff818a8aa3)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff818ac22a)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff818aedd7)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff818b050c)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b9087)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff818b9836)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff818bcdad)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818be5c3)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff818bf0ec)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c5dc9)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff818c8150)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff818c9a94)
Location: include/linux/ipv6.h:315
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (ffffffff818272c0)
Location: include/linux/ipv6.h:328
Inline: True
```
```
In net/core/sock.c (ffffffff8182b580)
Location: include/linux/ipv6.h:328
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189d20d)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff818a6ab0)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff818b48ac)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bde2b)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff818be4bd)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff818c5298)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff818e32b6)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81906d55)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81908776)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff8190cb4a)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81918f80)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8192512e)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81926dc5)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff8192b563)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff8192eb5a)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81931ada)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81932e3c)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193bfa8)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff8193c7b6)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff8193fecd)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81941703)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff8194222c)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff8194915b)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff8194b700)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff8194d124)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (ffffffff81870662)
Location: include/linux/ipv6.h:328
Inline: True
```
```
In net/core/sock.c (ffffffff81875aab)
Location: include/linux/ipv6.h:328
Inline: True
```
```
In net/core/filter.c (ffffffff818b20a9)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffff818c4119)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f16cd)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff818fbbab)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8190a473)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912861)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff8191418d)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff8191ac68)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81939c56)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff8195dd45)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff8195f975)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81963f28)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff819777f5)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197d4ee)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff8197f184)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819838d7)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819877ea)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff8198a5a4)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8198b8ec)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81995388)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81995839)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81998d03)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8199a519)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff8199b04d)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a2297)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff819a49b0)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff819a67e4)
Location: include/linux/ipv6.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (ffffffff81891232)
Location: include/linux/ipv6.h:329
Inline: True
```
```
In net/core/sock.c (ffffffff8189629b)
Location: include/linux/ipv6.h:329
Inline: True
```
```
In net/core/filter.c (ffffffff818d6bed)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffff818ed1a6)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191f22d)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81929b34)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8193871b)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941030)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff8194293d)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff8194942a)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff819698e3)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81992885)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff819945d5)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81998eb3)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff819ad3f5)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b33be)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff819b5754)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819b9dd7)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819be10a)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff819c0e3e)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c258c)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbc6e)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff819cc126)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff819cf653)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d0e69)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d19ad)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d8ef4)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff819db4c0)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff819dd344)
Location: include/linux/ipv6.h:329
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (ffffffff818daf22)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/sock.c (ffffffff818e0a37)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/filter.c (ffffffff819243db)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffff8193d75d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981b7d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff8198cd3f)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8199b7c8)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a567e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819a6f0d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff819ada7a)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff819d054e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819fe1a5)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81a000d5)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a04d06)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81a1a575)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a21a9e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81a24223)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a28f16)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a2d3a9)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a2fb75)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a3137c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a38b5c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81a3ac07)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a3e3b3)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3fbfa)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a407ed)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a47768)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff81a4a130)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a4c344)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (ffffffff8190d072)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/sock.c (ffffffff819128fd)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/filter.c (ffffffff819566eb)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffff819705ed)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b83bd)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff819c36de)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819d21fe)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc36d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819ddbdd)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff819e478d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81a0709e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a34d95)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81a36cb5)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b906)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81a511e5)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a5850e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81a5aca3)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a5fa66)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a63f09)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a666c5)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a67ecc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6f6cc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81a71887)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a75023)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a7686a)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a773ce)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e2e8)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff81a80cf0)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a82f14)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (ffffffff819dedb2)
Location: include/linux/ipv6.h:337
Inline: True
```
```
In net/core/sock.c (ffffffff819e479d)
Location: include/linux/ipv6.h:337
Inline: True
```
```
In net/core/filter.c (ffffffff81a29eea)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffff81a44433)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2cd4)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81aaede2)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1afa)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac94cd)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81acaedd)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff81ad2240)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81af769e)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f075)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff81b29c05)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81b2bf75)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b30ed0)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81b48905)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b50a3e)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81b539b3)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b5856a)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b5c97c)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81b5f05c)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b601cc)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b695ae)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81b6b17a)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6f25f)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_flow_key_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70ad5)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b7165e)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b78eda)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81b7b973)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b7d3d5)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81ba9cc5)
Location: include/linux/ipv6.h:337
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
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
In net/socket.c (ffffffff819de642)
Location: include/linux/ipv6.h:326
Inline: True
```
```
In net/core/sock.c (ffffffff819e402d)
Location: include/linux/ipv6.h:326
Inline: True
```
```
In net/core/filter.c (ffffffff81a2a84a)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffff81a481a3)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacfe4)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81ab9040)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81acd557)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad541d)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad7441)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff81ade37a)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81b0457e)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d935)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff81b38545)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81b3a995)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b3fb00)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81b574e5)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5fd85)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81b61f43)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b66baa)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b6b1cc)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81b6d7ec)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b6e93c)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b76ff5)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81b79bfa)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b7dd8f)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_flow_key_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7fdad)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_renew
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b802ee)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b87e5a)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81b8a9b3)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b8c575)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81bb9c95)
Location: include/linux/ipv6.h:326
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
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
In net/socket.c (ffffffff819c4652)
Location: include/linux/ipv6.h:327
Inline: True
```
```
In net/core/sock.c (ffffffff819ca0bd)
Location: include/linux/ipv6.h:327
Inline: True
```
```
In net/core/filter.c (ffffffff81a119d6)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffff81a2d0fe)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a98234)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81aa42f3)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ab5884)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac049a)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac252e)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff81ac999a)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81aef58e)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b998)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff81b261e5)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81b28675)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d98e)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81b450d5)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4e065)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81b501f3)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b54d87)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b59519)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81b5bb84)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b5cd3c)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b65b15)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81b68727)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6c993)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6e8bd)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b6eeee)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76c30)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81b79820)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b7b5a7)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81ba8f75)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8160)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
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
In net/socket.c (ffffffff81a73a42)
Location: include/linux/ipv6.h:331
Inline: True
```
```
In net/core/sock.c (ffffffff81a79605)
Location: include/linux/ipv6.h:331
Inline: True
```
```
In net/core/filter.c (ffffffff81acd6aa)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffff81ae26f9)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b5373d)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81b604c8)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81b728a4)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7f448)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81b80297)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff81b8820e)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81bb0b11)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_output.c (ffffffff81be031f)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff81becc85)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81bee625)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3bda)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81c0c215)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c15395)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81c177ec)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81c1d854)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81c20b37)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81c232c2)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81c25ab0)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2c535)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81c303e4)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81c34893)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c3691d)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81c36f7b)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c416a2)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81c444bd)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81c46555)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81c779c5)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
```
```
In net/mptcp/pm_netlink.c (ffffffff81c877e0)
Location: include/linux/ipv6.h:331
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
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
In net/socket.c (ffffffff81be682e)
Location: include/linux/ipv6.h:334
Inline: True
```
```
In net/core/sock.c (ffffffff81bece19)
Location: include/linux/ipv6.h:334
Inline: True
```
```
In net/core/filter.c (ffffffff81c4b977)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffff81c662e8)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ce11d2)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81ceedee)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81d01ded)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0edfe)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81d1067b)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff81d196ea)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81d4408b)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_output.c (ffffffff81d771eb)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff81d85155)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81d86b95)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c81c)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81da70b5)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db0b95)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81db3615)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81db9e22)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81dbd8cc)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81dc01cc)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81dc2b40)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcbf3d)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81dcda74)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81dd21f3)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd4431)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81dd4b7d)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddfd85)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81de348e)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81de59ec)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81e1cc75)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2dff0)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
```
```
In net/mptcp/sockopt.c (ffffffff81e33abe)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35e27)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
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
In net/socket.c (ffffffff81d92cbe)
Location: include/linux/ipv6.h:334
Inline: True
```
```
In net/core/sock.c (ffffffff81d9a859)
Location: include/linux/ipv6.h:334
Inline: True
```
```
In net/core/net-traces.c (ffffffff81e1d045)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea15e2)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea4efc)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
```
```
In net/ipv4/tcp_output.c (ffffffff81ec70ba)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4943)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed639b)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff81ee007a)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81f0d55a)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43a6b)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff81f52b95)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81f54735)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a80c)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81f766b5)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f81473)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81f82f85)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81f89ed2)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81f8de1c)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81f9093c)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81f92ba0)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d055)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81f9ec44)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81fa3673)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa5a61)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81fa622d)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb20a5)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81fb5b0e)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81fb820c)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81ffa995)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
```
```
In net/mptcp/pm_netlink.c (ffffffff8200af96)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
```
```
In net/mptcp/sockopt.c (ffffffff8200bbde)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
```
```
In net/mptcp/pm_userspace.c (ffffffff8200ead1)
Location: include/linux/ipv6.h:334
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
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
In net/socket.c (ffffffff81e0100e)
Location: include/linux/ipv6.h:327
Inline: True
```
```
In net/core/sock.c (ffffffff81e090a9)
Location: include/linux/ipv6.h:327
Inline: True
```
```
In net/core/net-traces.c (ffffffff81e91945)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff81effde1)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f00d83)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_reset_saddr
```
```
In net/ipv4/tcp_output.c (ffffffff81f25970)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32777)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81f352bb)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff81f3f413)
Location: include/linux/ipv6.h:327
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81f6d1ba)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa323f)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2595)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:inet_reset_saddr
```
```
In net/ipv6/anycast.c (ffffffff81fb4155)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81fba566)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81fd66c5)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe1743)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81fe3285)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81fe9822)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81fee5fc)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81ff11bc)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81ff3e7c)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffdae5)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81fff704)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff82003f10)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82006297)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff82006aad)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff820127b1)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff8201621e)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff8201898c)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff820708c5)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
```
```
In net/mptcp/pm_netlink.c (ffffffff820873c6)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
```
```
In net/mptcp/sockopt.c (ffffffff82087e04)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_get_sub_addrs
```
```
In net/mptcp/pm_userspace.c (ffffffff8208b651)
Location: include/linux/ipv6.h:327
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
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
In net/socket.c (ffffffff81ebd70e)
Location: include/linux/ipv6.h:313
Inline: True
```
```
In net/core/net-traces.c (ffffffff81f53d05)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc3f33)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc5003)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_reset_saddr
```
```
In net/ipv4/tcp_output.c (ffffffff81fea255)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff876b)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffb43b)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff82007916)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff820339b1)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_output.c (ffffffff820708d9)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff8207fd25)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:inet_reset_saddr
```
```
In net/ipv6/anycast.c (ffffffff82081a05)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff82082a95)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff820a4045)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820af663)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff820b11a5)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff820b7772)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff820bc1ec)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff820bed9a)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff820c1efc)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc976)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff820ce4c4)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff820d2cd0)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d50f7)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff820d590d)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e19bd)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff820e534c)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff820e795c)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff8214c30f)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
```
```
In net/mptcp/pm_netlink.c (ffffffff8215cc0e)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
```
```
In net/mptcp/sockopt.c (ffffffff8215d854)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_get_sub_addrs
```
```
In net/mptcp/pm_userspace.c (ffffffff82161388)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
```
```
In net/handshake/trace.c (ffffffff8216cb7a)
Location: include/linux/ipv6.h:313
Inline: True
Inline callers:
  - net/handshake/trace.c:perf_trace_tls_contenttype
  - net/handshake/trace.c:perf_trace_handshake_alert_class
  - net/handshake/trace.c:trace_event_raw_event_tls_contenttype
  - net/handshake/trace.c:trace_event_raw_event_handshake_alert_class
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
In net/socket.c (ffff800010ba1fa8)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/sock.c (ffff800010bab318)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/filter.c (ffff800010bf7fd0)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/net-traces.c (ffff800010c19454)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffff800010c69760)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffff800010c76294)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffff800010c84c0c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c90268)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffff800010c910b4)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffff800010c997f8)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffff800010cbffd4)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffff800010cf56fc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffff800010cf795c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffff800010cfcae8)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffff800010d15130)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1de98)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffff800010d20024)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d252bc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d29fbc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffff800010d2c634)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d2dd3c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38194)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffff800010d3a2ec)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffff800010d3da3c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3fb50)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffff800010d40a34)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffff800010d4971c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffff800010d4c554)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffff800010d4dcb4)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (c0cc3fd0)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/sock.c (c0cc8d18)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/filter.c (c0d11a8c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/net-traces.c (c0d2ea8c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (c0d7899c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (c0d849d8)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (c0d93f08)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (c0d9e454)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (c0d9fd44)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (c0da989c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (c0dcc4c8)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (c0dfc14c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (c0dfdfb4)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (c0e03fc0)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (c0e1ada4)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (c0e22498)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (c0e24be0)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c0e289cc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2df04)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (c0e3050c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e31c28)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (c0e3b45c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (c0e3c7fc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (c0e40c8c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (c0e42814)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (c0e434ac)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (c0e4aaa4)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_dontfrag
```
```
In net/ipv6/syncookies.c (c0e4d810)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (c0e4fa60)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (c000000000c76c80)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/sock.c (c000000000c80134)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/filter.c (c000000000cde8dc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/net-traces.c (c000000000d059b4)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e470)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (c000000000d7dd64)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (c000000000d90c90)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e2a0)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (c000000000da0714)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (c000000000daac60)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (c000000000ddb350)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (c000000000e1b8a8)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (c000000000e1e38c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (c000000000e24800)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (c000000000e42068)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4c0f4)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (c000000000e4e7f8)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c000000000e54c0c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c000000000e5af20)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (c000000000e5defc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c000000000e5faf0)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b8c0)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (c000000000e6d500)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (c000000000e71ee4)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e74240)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (c000000000e750cc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (c000000000e7edd0)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (c000000000e82c00)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (c000000000e85e5c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (ffffffe00073a0a8)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/sock.c (ffffffe00073da38)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/filter.c (ffffffe000779a2c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffe0007924da)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf5ca)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffe0007d9428)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffe0007e658a)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef6f8)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffe0007f0ea0)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffe0007f7066)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffe000816a60)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffe000841114)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffe000842c82)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffe0008472ba)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffe00085a7fc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe000860a14)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffe000862168)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffe000865d5c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffe00086a79e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffe00086c88c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffe00086dda2)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875372)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffe000876f8c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffe00087a110)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087b8be)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffe00087c2cc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882b9a)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffe0008852d8)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffe0008863e0)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (ffffffff818ad072)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/sock.c (ffffffff818b28fd)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/filter.c (ffffffff818f66bb)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffff819105bd)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff8195822d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff8196354e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8197206e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c1dd)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff8197da4d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff819845fd)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff819a6e3e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819d4425)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff819d6345)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff819daf96)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff819f0875)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f7b9e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff819fa333)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819ff0f6)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a03599)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a05d55)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a0755c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ed5c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81a10f17)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a146b3)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a15efa)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a16a5e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1d978)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff81a20380)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a225a4)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (ffffffff81866fc2)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/sock.c (ffffffff8186c84d)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/filter.c (ffffffff818b04eb)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffff818ca37d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911d1d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff8191d03e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8192bb3e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81935c9d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff8193750d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff8193e0bd)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff819608fe)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819911e5)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81993105)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81997d56)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff819ad635)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b495e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff819b70f3)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bbeb6)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819c0359)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff819c2b15)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c431c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbb1c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff819cdcd7)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff819d1473)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d2cba)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d381e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff819da738)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff819dd140)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff819df364)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (ffffffff818fe072)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/sock.c (ffffffff819038fd)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/filter.c (ffffffff819476eb)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffff819615ed)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a445b)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c29fd)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff819cdd1e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819dc83e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e69ad)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819e821d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff819eedcd)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81a116de)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a3eea5)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81a40dc5)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a45a16)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81a5b2f5)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6261e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81a64db3)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a69b76)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a6e019)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a707d5)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a71fdc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a797dc)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81a7b997)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a7f133)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8097a)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a814de)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a883f8)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff81a8ae00)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a8d024)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
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
In net/socket.c (ffffffff8191f102)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/sock.c (ffffffff819248fd)
Location: include/linux/ipv6.h:336
Inline: True
```
```
In net/core/filter.c (ffffffff81968ffb)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/net-traces.c (ffffffff8198385d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc3fd)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff819d78ae)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819e64be)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f066d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819f1f4d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_init_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff819f8f3d)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81a1c04e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a4a965)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81a4c9c5)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a516e6)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81a675d5)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6eb1e)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81a712e3)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a76186)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a7a659)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a7cdf5)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a7e60c)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a85fac)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81a881e7)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a8b9f3)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_common_ctl
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8d23a)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a8ddce)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a95048)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff81a97a60)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a99ce4)
Location: include/linux/ipv6.h:336
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
</details>
</li>
</ul>

## Differences
