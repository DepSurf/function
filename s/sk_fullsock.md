# Function: <code>sk_fullsock</code>

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
In drivers/net/tun.c (ffffffff815ee8f3)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/sock.c (ffffffff817014d7)
Location: include/net/sock.h:2237
Inline: True
```
```
In net/core/dev.c (ffffffff8171561d)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_pick_tx
```
```
In net/ipv4/ip_output.c (ffffffff8175c732)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761e45)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81768344)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff817760be)
Location: include/net/sock.h:2237
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
In net/ipv4/tcp_ipv4.c (ffffffff8177e2c6)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81780044)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff817806cb)
Location: include/net/sock.h:2237
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
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff817a2d1e)
Location: include/net/sock.h:2237
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
Location: include/net/sock.h:2237
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
In net/ipv6/anycast.c (ffffffff817c3dd1)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_close
```
```
In net/ipv6/ip6_output.c (ffffffff817c4586)
Location: include/net/sock.h:2237
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
Location: include/net/sock.h:2237
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817dc13e)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff817de5e4)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_na
```
```
In net/ipv6/udp.c (ffffffff817e1c84)
Location: include/net/sock.h:2237
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
In net/ipv6/raw.c (ffffffff817e517e)
Location: include/net/sock.h:2237
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
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/mcast.c (ffffffff817e9853)
Location: include/net/sock.h:2237
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
In net/ipv6/tcp_ipv6.c (ffffffff817ef908)
Location: include/net/sock.h:2237
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
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff817f4076)
Location: include/net/sock.h:2237
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
In net/ipv6/ip6_flowlabel.c (ffffffff817f6271)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff817f7327)
Location: include/net/sock.h:2237
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
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff817ff2b6)
Location: include/net/sock.h:2237
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
Location: include/net/sock.h:2219
Inline: True
```
```
In net/core/dev.c (ffffffff8177d64d)
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_pick_tx
```
```
In net/core/filter.c (ffffffff8179b619)
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/ip_output.c (ffffffff817c9521)
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff817ce185)
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff817d4c25)
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff817e5030)
Location: include/net/sock.h:2219
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
In net/ipv4/tcp_ipv4.c (ffffffff817eb716)
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ed566)
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff817edc7c)
Location: include/net/sock.h:2219
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
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81810536)
Location: include/net/sock.h:2219
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
Location: include/net/sock.h:2219
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
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff818355f1)
Location: include/net/sock.h:2219
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
Location: include/net/sock.h:2219
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184ae1e)
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff8184c4f5)
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81850429)
Location: include/net/sock.h:2219
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
Location: include/net/sock.h:2219
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
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8185809c)
Location: include/net/sock.h:2219
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
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
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
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81864170)
Location: include/net/sock.h:2219
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
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff8186684b)
Location: include/net/sock.h:2219
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
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff8186ec39)
Location: include/net/sock.h:2219
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff818702b4)
Location: include/net/sock.h:2219
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
In kernel/bpf/cgroup.c (ffffffff811975de)
Location: include/net/sock.h:2286
Inline: True
```
```
In net/core/sock.c (ffffffff81795627)
Location: include/net/sock.h:2286
Inline: True
```
```
In net/core/dev.c (ffffffff817aab8c)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_pick_tx
```
```
In net/core/filter.c (ffffffff817c9616)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/ip_output.c (ffffffff817f94b1)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdeeb)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81804938)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff818154ba)
Location: include/net/sock.h:2286
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
In net/ipv4/tcp_ipv4.c (ffffffff8181c086)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181de76)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff8181e5fc)
Location: include/net/sock.h:2286
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
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81841a36)
Location: include/net/sock.h:2286
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
Location: include/net/sock.h:2286
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
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81867121)
Location: include/net/sock.h:2286
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
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187ccbe)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff8187e3c5)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81882239)
Location: include/net/sock.h:2286
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
Location: include/net/sock.h:2286
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
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8188a15c)
Location: include/net/sock.h:2286
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
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81896820)
Location: include/net/sock.h:2286
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
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81898f4b)
Location: include/net/sock.h:2286
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
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff818a1b89)
Location: include/net/sock.h:2286
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff818a3224)
Location: include/net/sock.h:2286
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
In kernel/bpf/cgroup.c (ffffffff8119f27e)
Location: include/net/sock.h:2313
Inline: True
```
```
In net/socket.c (ffffffff817af180)
Location: include/net/sock.h:2313
Inline: True
```
```
In net/core/sock.c (ffffffff817b32a0)
Location: include/net/sock.h:2313
Inline: True
```
```
In net/core/dev.c (ffffffff817c91de)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_pick_tx
```
```
In net/core/filter.c (ffffffff817e9695)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/ip_output.c (ffffffff81819909)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e303)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81824c8a)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8182ca70)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_output.c (ffffffff81834fa0)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c852)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183da51)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff8183ec6d)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81841139)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/udp.c (ffffffff81845832)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81863186)
Location: include/net/sock.h:2313
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
In net/ipv4/xfrm4_output.c (ffffffff8187255e)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (ffffffff81885ba5)
Location: include/net/sock.h:2313
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
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff8188b8a7)
Location: include/net/sock.h:2313
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81897c00)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a27be)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff818a4415)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff818a8aa3)
Location: include/net/sock.h:2313
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
Location: include/net/sock.h:2313
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
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff818b050c)
Location: include/net/sock.h:2313
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
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff818bcdad)
Location: include/net/sock.h:2313
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
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff818bf0ec)
Location: include/net/sock.h:2313
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
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff818c8150)
Location: include/net/sock.h:2313
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff818c9a94)
Location: include/net/sock.h:2313
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
In kernel/bpf/cgroup.c (ffffffff811b246e)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff818272c0)
Location: include/net/sock.h:2327
Inline: True
```
```
In net/core/sock.c (ffffffff8182cc70)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffff81842e7e)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_pick_tx
```
```
In net/core/filter.c (ffffffff81864d79)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/ipv4/ip_output.c (ffffffff81897f39)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189d20d)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff818a6ab0)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_init_transfer
  - net/ipv4/tcp.c:tcp_init_transfer
```
```
In net/ipv4/tcp_input.c (ffffffff818ab9ac)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff818b4420)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bbf93)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bdb17)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff818be4bd)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/ipv4/udp.c (ffffffff818c5298)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff818e32b6)
Location: include/net/sock.h:2327
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
In net/ipv4/xfrm4_output.c (ffffffff818f2f54)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (ffffffff81906d55)
Location: include/net/sock.h:2327
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
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff8190cb4a)
Location: include/net/sock.h:2327
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81918f80)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8192512e)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81926dc5)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff8192b563)
Location: include/net/sock.h:2327
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
Location: include/net/sock.h:2327
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
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81932e3c)
Location: include/net/sock.h:2327
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
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff8193fecd)
Location: include/net/sock.h:2327
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
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff8194222c)
Location: include/net/sock.h:2327
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
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff8194b700)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff8194d124)
Location: include/net/sock.h:2327
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
In kernel/bpf/cgroup.c (ffffffff811d1afe)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff81870662)
Location: include/net/sock.h:2334
Inline: True
```
```
In net/core/sock.c (ffffffff81876a5c)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffff8188d239)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff818aeab5)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/net-traces.c (ffffffff818c4119)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_output.c (ffffffff818ec1d5)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f16cd)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff818fbbab)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_init_transfer
  - net/ipv4/tcp.c:tcp_init_transfer
```
```
In net/ipv4/tcp_input.c (ffffffff81900d50)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81909a41)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8190d227)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8191196a)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819139bf)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff8191418d)
Location: include/net/sock.h:2334
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
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/ping.c (ffffffff81939c56)
Location: include/net/sock.h:2334
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
In net/ipv4/xfrm4_output.c (ffffffff8194986a)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (ffffffff8195dd45)
Location: include/net/sock.h:2334
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
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81963f28)
Location: include/net/sock.h:2334
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff819777f5)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197d4ee)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff8197f184)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819838d7)
Location: include/net/sock.h:2334
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
Location: include/net/sock.h:2334
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
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8198b8ec)
Location: include/net/sock.h:2334
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
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81998d03)
Location: include/net/sock.h:2334
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
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff8199b04d)
Location: include/net/sock.h:2334
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
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff819a49b0)
Location: include/net/sock.h:2334
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff819a67e4)
Location: include/net/sock.h:2334
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
In kernel/bpf/cgroup.c (ffffffff811e181e)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff81891232)
Location: include/net/sock.h:2465
Inline: True
```
```
In net/core/sock.c (ffffffff8189722c)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffff818ae554)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff818d2df5)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/net-traces.c (ffffffff818ed1a6)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_output.c (ffffffff81919375)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191f22d)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81929b34)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_init_transfer
  - net/ipv4/tcp.c:tcp_init_transfer
```
```
In net/ipv4/tcp_input.c (ffffffff8192ef60)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81937cf1)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8193b592)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940154)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8194216f)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff8194293d)
Location: include/net/sock.h:2465
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
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81959890)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff819698e3)
Location: include/net/sock.h:2465
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
In net/ipv4/xfrm4_output.c (ffffffff8197b527)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (ffffffff81992885)
Location: include/net/sock.h:2465
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
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81998eb3)
Location: include/net/sock.h:2465
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff819ad3f5)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b33be)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff819b5754)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819b9dd7)
Location: include/net/sock.h:2465
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
Location: include/net/sock.h:2465
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
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c258c)
Location: include/net/sock.h:2465
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
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff819cf653)
Location: include/net/sock.h:2465
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
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d19ad)
Location: include/net/sock.h:2465
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
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff819db4c0)
Location: include/net/sock.h:2465
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff819dd344)
Location: include/net/sock.h:2465
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
In kernel/bpf/cgroup.c (ffffffff811f88fe)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff818daf22)
Location: include/net/sock.h:2478
Inline: True
```
```
In net/core/sock.c (ffffffff818e167c)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffff818f9e8b)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff8191ff15)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff8193d75d)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_output.c (ffffffff8197b6e6)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981b7d)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff8198cd3f)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819924f4)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff8199b417)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f987)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4668)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a676a)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819a6f0d)
Location: include/net/sock.h:2478
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
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff819be34f)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff819d054e)
Location: include/net/sock.h:2478
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
In net/ipv4/xfrm4_output.c (ffffffff819e4a57)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (ffffffff819fe1a5)
Location: include/net/sock.h:2478
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
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a04d06)
Location: include/net/sock.h:2478
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81a1a575)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a21a9e)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81a24223)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a28f16)
Location: include/net/sock.h:2478
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
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a2fb75)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a3137c)
Location: include/net/sock.h:2478
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
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81a3ac07)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a3e3b3)
Location: include/net/sock.h:2478
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
Location: include/net/sock.h:2478
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
Location: include/net/sock.h:2478
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
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff81a4a130)
Location: include/net/sock.h:2478
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a4c344)
Location: include/net/sock.h:2478
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
In kernel/bpf/cgroup.c (ffffffff8120592e)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff8190d072)
Location: include/net/sock.h:2499
Inline: True
```
```
In net/core/sock.c (ffffffff8191386c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffff8192bfeb)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81952145)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff819705ed)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_output.c (ffffffff819b1ddb)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b83bd)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff819c36de)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819c8bad)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff819d1e37)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff819d6539)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db368)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dcb91)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819ddbdd)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff819f4f7f)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff81a0709e)
Location: include/net/sock.h:2499
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
In net/ipv4/xfrm4_output.c (ffffffff81a1ba77)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (ffffffff81a34d95)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b906)
Location: include/net/sock.h:2499
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81a511e5)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a5850e)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81a5aca3)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a5fa66)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a67ecc)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81a71887)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a75023)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff81a80cf0)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a82f14)
Location: include/net/sock.h:2499
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
In kernel/bpf/cgroup.c (ffffffff8122cb3e)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff819dedb2)
Location: include/net/sock.h:2549
Inline: True
```
```
In net/core/sock.c (ffffffff819e4d39)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/core/sock.c:sock_pfree
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffff819ff5bf)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81a2ba0d)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff81a44433)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/core/sock_map.c (ffffffff81a4efa5)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9c66b)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2cd4)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81aaede2)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81ab44f5)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81abed76)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac25d8)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8b4d)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81aca6a9)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81acaedd)
Location: include/net/sock.h:2549
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
In net/ipv4/udp.c (ffffffff81ad7833)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81ae310f)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff81af769e)
Location: include/net/sock.h:2549
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
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff81b29c05)
Location: include/net/sock.h:2549
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
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b30ed0)
Location: include/net/sock.h:2549
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81b48905)
Location: include/net/sock.h:2549
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
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81b539b3)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b5856a)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b5c97c)
Location: include/net/sock.h:2549
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
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b601cc)
Location: include/net/sock.h:2549
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
In net/ipv6/tcp_ipv6.c (ffffffff81b6a794)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81b6b17a)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6f25f)
Location: include/net/sock.h:2549
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
Location: include/net/sock.h:2549
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
Location: include/net/sock.h:2549
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
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81b7b973)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b7d3d5)
Location: include/net/sock.h:2549
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81ba9cc5)
Location: include/net/sock.h:2549
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
In kernel/bpf/cgroup.c (ffffffff81234fbe)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff819de642)
Location: include/net/sock.h:2570
Inline: True
```
```
In net/core/sock.c (ffffffff819e4489)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/core/sock.c:sock_pfree
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffff819ff322)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81a27d90)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_to_udp6_sock
  - net/core/filter.c:bpf_skc_to_tcp_sock
  - net/core/filter.c:bpf_skc_to_tcp6_sock
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff81a481a3)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/core/sock_map.c (ffffffff81a54b8c)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69fb1)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/ipv4/ip_output.c (ffffffff81aa64cb)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacfe4)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81ab9040)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81abee0c)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81aca6d4)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
  - net/ipv4/tcp_output.c:tcp_ecn_send_syn
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace087)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4aed)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad6607)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad7441)
Location: include/net/sock.h:2570
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
In net/ipv4/udp.c (ffffffff81ae3e83)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81aeffef)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff81b0457e)
Location: include/net/sock.h:2570
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
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff81b38545)
Location: include/net/sock.h:2570
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
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b3fb00)
Location: include/net/sock.h:2570
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81b574e5)
Location: include/net/sock.h:2570
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
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81b61f43)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b66baa)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b6b1cc)
Location: include/net/sock.h:2570
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
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b6e93c)
Location: include/net/sock.h:2570
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
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81b79bfa)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b7dd8f)
Location: include/net/sock.h:2570
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
Location: include/net/sock.h:2570
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
Location: include/net/sock.h:2570
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
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81b8a9b3)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b8c575)
Location: include/net/sock.h:2570
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81bb9c95)
Location: include/net/sock.h:2570
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
In kernel/bpf/cgroup.c (ffffffff812396ca)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff819c4652)
Location: include/net/sock.h:2606
Inline: True
```
```
In net/core/sock.c (ffffffff819ca699)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/core/sock.c:sock_pfree
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffff819e5afb)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81a0f110)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_to_udp6_sock
  - net/core/filter.c:bpf_skc_to_tcp_sock
  - net/core/filter.c:bpf_skc_to_tcp6_sock
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff81a2d0fe)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/core/sock_map.c (ffffffff81a5104c)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/core/bpf_sk_storage.c (ffffffff81a524b1)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/ipv4/ip_output.c (ffffffff81a9073b)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a98234)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81aa42f3)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81aab0f2)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81ab5555)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab9222)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfb9a)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac1676)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac252e)
Location: include/net/sock.h:2606
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
In net/ipv4/udp.c (ffffffff81acf070)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81adb72f)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff81aef58e)
Location: include/net/sock.h:2606
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
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff81b261e5)
Location: include/net/sock.h:2606
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
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d98e)
Location: include/net/sock.h:2606
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
In net/ipv6/route.c (ffffffff81b450d5)
Location: include/net/sock.h:2606
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
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81b501f3)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b54d87)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b59519)
Location: include/net/sock.h:2606
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
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b5cd3c)
Location: include/net/sock.h:2606
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
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81b68727)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6c993)
Location: include/net/sock.h:2606
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
Location: include/net/sock.h:2606
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
Location: include/net/sock.h:2606
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
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81b79820)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b7b5a7)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81ba8f75)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8160)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
bool sk_fullsock(const struct sock *sk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81273ee1)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff81a73a42)
Location: include/net/sock.h:2665
Inline: True
```
```
In net/core/sock.c (ffffffff81a79e87)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/core/sock.c:sock_pfree
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffff81a95fdb)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81acbb3e)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_to_udp6_sock
  - net/core/filter.c:bpf_skc_to_tcp_sock
  - net/core/filter.c:bpf_skc_to_tcp6_sock
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff81ae26f9)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/core/sock_map.c (ffffffff81b09390)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b5bc)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f301)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_output.c (ffffffff81b4b8a5)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b5373d)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81b604c8)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81b6716f)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
Direct callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81b72556)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76542)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7a107)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7f0e0)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81b80297)
Location: include/net/sock.h:2665
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
In net/ipv4/udp.c (ffffffff81b8db54)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81b9b6ad)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff81bb0b11)
Location: include/net/sock.h:2665
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
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/ipv6/af_inet6.c (ffffffff81becc85)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
Direct callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81bee625)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3bda)
Location: include/net/sock.h:2665
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
In net/ipv6/route.c (ffffffff81c0c215)
Location: include/net/sock.h:2665
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
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81c177ec)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81c1d854)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81c20b37)
Location: include/net/sock.h:2665
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
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81c25ab0)
Location: include/net/sock.h:2665
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
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81c303e4)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81c34893)
Location: include/net/sock.h:2665
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
Location: include/net/sock.h:2665
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
Location: include/net/sock.h:2665
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
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81c444bd)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81c46555)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81c779c5)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/pm_netlink.c (ffffffff81c877e0)
Location: include/net/sock.h:2665
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
```
**Symbols:**

```
ffffffff81b61e40-ffffffff81b61e5d: sk_fullsock (STB_LOCAL)
ffffffff81d3a729-ffffffff81d3a75a: sk_fullsock.cold (STB_LOCAL)
ffffffff81bebe50-ffffffff81bebe6d: sk_fullsock (STB_LOCAL)
ffffffff81d3f050-ffffffff81d3f081: sk_fullsock.cold (STB_LOCAL)
ffffffff81c21d90-ffffffff81c21dad: sk_fullsock (STB_LOCAL)
ffffffff81d408d6-ffffffff81d40907: sk_fullsock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
bool sk_fullsock(const struct sock *sk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c2120)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff81be682e)
Location: include/net/sock.h:2775
Inline: True
```
```
In net/core/sock.c (ffffffff81bece19)
Location: include/net/sock.h:2775
Inline: True
```
```
In net/core/dev.c (ffffffff81c0ca42)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81c47d91)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_to_unix_sock
  - net/core/filter.c:bpf_skc_to_udp6_sock
  - net/core/filter.c:bpf_skc_to_tcp_sock
  - net/core/filter.c:bpf_skc_to_tcp6_sock
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_getsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff81c662e8)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/core/sock_map.c (ffffffff81c8f45f)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91bbb)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/netfilter/nf_queue.c (ffffffff81ccba65)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_output.c (ffffffff81cd8f22)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ce11d2)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff81ceef75)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81cf63d0)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
Direct callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81d01c47)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05fa2)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a28f)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0ea32)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81d1067b)
Location: include/net/sock.h:2775
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
In net/ipv4/udp.c (ffffffff81d1ecfc)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81d2d354)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff81d4408b)
Location: include/net/sock.h:2775
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
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff81d85155)
Location: include/net/sock.h:2775
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
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c81c)
Location: include/net/sock.h:2775
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81da70b5)
Location: include/net/sock.h:2775
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
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81db3615)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81db9e22)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81dbd8cc)
Location: include/net/sock.h:2775
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
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81dc2b40)
Location: include/net/sock.h:2775
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
In net/ipv6/tcp_ipv6.c (ffffffff81dcd6b6)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81dcda74)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81dd21f3)
Location: include/net/sock.h:2775
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
Location: include/net/sock.h:2775
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
Location: include/net/sock.h:2775
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
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81de348e)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81de59ec)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81e1cc75)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2dff0)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
```
```
In net/mptcp/sockopt.c (ffffffff81e33abe)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35e27)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
```
```
In net/mptcp/bpf.c (ffffffff81e36568)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/mptcp/bpf.c:bpf_mptcp_sock_from_subflow
```
**Symbols:**

```
ffffffff81cf0920-ffffffff81cf0949: sk_fullsock (STB_LOCAL)
ffffffff81f06f51-ffffffff81f06f8e: sk_fullsock.cold (STB_LOCAL)
ffffffff81d76810-ffffffff81d76839: sk_fullsock (STB_LOCAL)
ffffffff81f0b835-ffffffff81f0b872: sk_fullsock.cold (STB_LOCAL)
ffffffff81dbebc0-ffffffff81dbebe9: sk_fullsock (STB_LOCAL)
ffffffff81f0d2ce-ffffffff81f0d30b: sk_fullsock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
bool sk_fullsock(const struct sock *sk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81326920)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff81d92cbe)
Location: include/net/sock.h:2821
Inline: True
```
```
In net/core/sock.c (ffffffff81d9cabd)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff81dbc8a2)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81dfc4b1)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_to_unix_sock
  - net/core/filter.c:bpf_skc_to_udp6_sock
  - net/core/filter.c:bpf_skc_to_tcp_sock
  - net/core/filter.c:bpf_skc_to_tcp6_sock
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
  - net/core/filter.c:bpf_sk_getsockopt
  - net/core/filter.c:bpf_sk_setsockopt
  - net/core/filter.c:__bpf_getsockopt
  - net/core/filter.c:__bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff81e1d045)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/core/sock_map.c (ffffffff81e4a6ff)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4d18b)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b8b5)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_output.c (ffffffff81e9956c)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea15e2)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea4efc)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
```
```
In net/ipv4/tcp.c (ffffffff81eabfe1)
Location: include/net/sock.h:2821
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ebade0)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
Direct callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6dc7)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb2f3)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecfb0f)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4512)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed639b)
Location: include/net/sock.h:2821
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
In net/ipv4/tcp_fastopen.c (ffffffff81ed898f)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/udp.c (ffffffff81ee5ce8)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81ef47b4)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff81f0d55a)
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff81f52b95)
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a80c)
Location: include/net/sock.h:2821
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81f766b5)
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81f89ed2)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81f8de1c)
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81f92ba0)
Location: include/net/sock.h:2821
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
In net/ipv6/tcp_ipv6.c (ffffffff81f9e7be)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81f9ec44)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81fa3673)
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff81fb5b0e)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81fb820c)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff81ffa995)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/pm_netlink.c (ffffffff8200af96)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
```
```
In net/mptcp/sockopt.c (ffffffff8200bbde)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
```
```
In net/mptcp/pm_userspace.c (ffffffff8200ead1)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
```
```
In net/mptcp/bpf.c (ffffffff8200f568)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/mptcp/bpf.c:bpf_mptcp_sock_from_subflow
```
**Symbols:**

```
ffffffff81eb4fd0-ffffffff81eb4ff9: sk_fullsock (STB_LOCAL)
ffffffff820aea43-ffffffff820aea80: sk_fullsock.cold (STB_LOCAL)
ffffffff81f42f80-ffffffff81f42fa9: sk_fullsock (STB_LOCAL)
ffffffff820b309f-ffffffff820b30dc: sk_fullsock.cold (STB_LOCAL)
ffffffff81f8f130-ffffffff81f8f159: sk_fullsock (STB_LOCAL)
ffffffff820b4740-ffffffff820b477d: sk_fullsock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
bool sk_fullsock(const struct sock *sk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81356c6e)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff81e0100e)
Location: include/net/sock.h:2809
Inline: True
```
```
In net/core/sock.c (ffffffff81e0b315)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff81e2d0b2)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81e6d132)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_to_unix_sock
  - net/core/filter.c:bpf_skc_to_udp6_sock
  - net/core/filter.c:bpf_skc_to_tcp_sock
  - net/core/filter.c:bpf_skc_to_tcp6_sock
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:__bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
  - net/core/filter.c:bpf_sk_getsockopt
  - net/core/filter.c:bpf_sk_setsockopt
  - net/core/filter.c:__bpf_getsockopt
  - net/core/filter.c:__bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff81e91945)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/core/sock_map.c (ffffffff81ea5e0b)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea88a0)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/netfilter/nf_queue.c (ffffffff81ee98ff)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_output.c (ffffffff81ef7e78)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81effde1)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f00d83)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_reset_saddr
```
```
In net/ipv4/tcp.c (ffffffff81f0a861)
Location: include/net/sock.h:2809
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81f19271)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
Direct callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81f25685)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29d88)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2e7dd)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f3352a)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81f352bb)
Location: include/net/sock.h:2809
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
In net/ipv4/tcp_fastopen.c (ffffffff81f37a9f)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/udp.c (ffffffff81f455cb)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/af_inet.c (ffffffff81f5409b)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff81f6d1ba)
Location: include/net/sock.h:2809
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
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2595)
Location: include/net/sock.h:2809
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
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81fba566)
Location: include/net/sock.h:2809
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81fd66c5)
Location: include/net/sock.h:2809
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
Location: include/net/sock.h:2809
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
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81fe9822)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81fee5fc)
Location: include/net/sock.h:2809
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
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81ff3e7c)
Location: include/net/sock.h:2809
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
In net/ipv6/tcp_ipv6.c (ffffffff81fff27a)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81fff704)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff82003f10)
Location: include/net/sock.h:2809
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
Location: include/net/sock.h:2809
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
Location: include/net/sock.h:2809
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
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff8201621e)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff8201898c)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff820708c5)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/pm_netlink.c (ffffffff820873c6)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
```
```
In net/mptcp/sockopt.c (ffffffff82087e04)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_get_sub_addrs
```
```
In net/mptcp/pm_userspace.c (ffffffff8208b651)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
```
```
In net/mptcp/bpf.c (ffffffff8208c158)
Location: include/net/sock.h:2809
Inline: True
Inline callers:
  - net/mptcp/bpf.c:bpf_mptcp_sock_from_subflow
```
**Symbols:**

```
ffffffff81f13400-ffffffff81f13429: sk_fullsock (STB_LOCAL)
ffffffff8212fee1-ffffffff8212ff1e: sk_fullsock.cold (STB_LOCAL)
ffffffff81fa27a0-ffffffff81fa27c9: sk_fullsock (STB_LOCAL)
ffffffff821342a3-ffffffff821342e0: sk_fullsock.cold (STB_LOCAL)
ffffffff81fef930-ffffffff81fef959: sk_fullsock (STB_LOCAL)
ffffffff821357c3-ffffffff82135800: sk_fullsock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
bool sk_fullsock(const struct sock *sk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8137f79e)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff81ebd70e)
Location: include/net/sock.h:2821
Inline: True
```
```
In net/core/sock.c (ffffffff81ec7d05)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff81eeb3be)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81f2c562)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_to_unix_sock
  - net/core/filter.c:bpf_skc_to_udp6_sock
  - net/core/filter.c:bpf_skc_to_tcp_sock
  - net/core/filter.c:bpf_skc_to_tcp6_sock
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:__bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
  - net/core/filter.c:bpf_sk_getsockopt
  - net/core/filter.c:bpf_sk_setsockopt
  - net/core/filter.c:__bpf_getsockopt
  - net/core/filter.c:__bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff81f53d05)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/core/sock_map.c (ffffffff81f688cb)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6b360)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/netfilter/nf_queue.c (ffffffff81fad69e)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_output.c (ffffffff81fbbd2e)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc3f33)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc5003)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_reset_saddr
```
```
In net/ipv4/tcp.c (ffffffff81fce8e1)
Location: include/net/sock.h:2821
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81fddb20)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
Direct callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9f45)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee8f8)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff363d)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9692)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffb43b)
Location: include/net/sock.h:2821
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
In net/ipv4/tcp_fastopen.c (ffffffff81ffdb6f)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/udp.c (ffffffff8200b635)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff8201b852)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_listen_sk
  - net/ipv4/af_inet.c:__inet_listen_sk
```
```
In net/ipv4/ping.c (ffffffff820339b1)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_ao.c (ffffffff82059900)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_get_repair
  - net/ipv4/tcp_ao.c:tcp_ao_set_repair
  - net/ipv4/tcp_ao.c:tcp_ao_get_sock_info
  - net/ipv4/tcp_ao.c:tcp_ao_get_mkts
  - net/ipv4/tcp_ao.c:tcp_ao_del_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
```
```
In net/xfrm/xfrm_output.c (ffffffff820708d9)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/ipv6/af_inet6.c (ffffffff8207fd25)
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff82082a95)
Location: include/net/sock.h:2821
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff820a4045)
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff820b7772)
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff820c1efc)
Location: include/net/sock.h:2821
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
In net/ipv6/tcp_ipv6.c (ffffffff820cdf8a)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:__inet6_lookup_skb
  - net/ipv6/tcp_ipv6.c:__inet6_lookup_skb
```
```
In net/ipv6/ping.c (ffffffff820ce4c4)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff820d2cd0)
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
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
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
```
In net/ipv6/syncookies.c (ffffffff820e534c)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff820e795c)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/mptcp/protocol.c (ffffffff8214c30f)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:mptcp_copy_inaddrs
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In net/mptcp/pm_netlink.c (ffffffff8215cc0e)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
```
```
In net/mptcp/sockopt.c (ffffffff8215d854)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_get_sub_addrs
```
```
In net/mptcp/pm_userspace.c (ffffffff82161388)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
```
```
In net/mptcp/bpf.c (ffffffff82162618)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/mptcp/bpf.c:bpf_mptcp_sock_from_subflow
```
```
In net/handshake/trace.c (ffffffff8216cb7a)
Location: include/net/sock.h:2821
Inline: True
Inline callers:
  - net/handshake/trace.c:perf_trace_tls_contenttype
  - net/handshake/trace.c:perf_trace_handshake_alert_class
  - net/handshake/trace.c:trace_event_raw_event_tls_contenttype
  - net/handshake/trace.c:trace_event_raw_event_handshake_alert_class
```
**Symbols:**

```
ffffffff81fd78e0-ffffffff81fd7909: sk_fullsock (STB_LOCAL)
ffffffff82211bef-ffffffff82211c2c: sk_fullsock.cold (STB_LOCAL)
ffffffff820bd500-ffffffff820bd529: sk_fullsock (STB_LOCAL)
ffffffff8221729e-ffffffff822172db: sk_fullsock.cold (STB_LOCAL)
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
In kernel/bpf/cgroup.c (ffff80001028e89c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffff800010ba1fa8)
Location: include/net/sock.h:2499
Inline: True
```
```
In net/core/sock.c (ffff800010baaaa4)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffff800010bc86dc)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffff800010bf4390)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffff800010c19454)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_output.c (ffff800010c63ae4)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffff800010c69760)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffff800010c76294)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffff800010c7a7b4)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffff800010c84a18)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffff800010c892a0)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e750)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f76c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffff800010c910b4)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffff800010caae00)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffff800010cbffd4)
Location: include/net/sock.h:2499
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
In net/ipv4/xfrm4_output.c (ffff800010cd7d10)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (ffff800010cf56fc)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffff800010cfcae8)
Location: include/net/sock.h:2499
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffff800010d15130)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1de98)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffff800010d20024)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d252bc)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d2dd3c)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffff800010d3a2ec)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffff800010d3da3c)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffff800010d4c554)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffff800010d4dcb4)
Location: include/net/sock.h:2499
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
In kernel/bpf/cgroup.c (c04bda94)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (c0cc3fd0)
Location: include/net/sock.h:2499
Inline: True
```
```
In net/core/sock.c (c0cc9d5c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (c0ce3f4c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (c0d0cb18)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (c0d2ea8c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_output.c (c0d71fc8)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (c0d7899c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (c0d849d8)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (c0d88734)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (c0d93ce8)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (c0d98314)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c0d9d6a8)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (c0d9f520)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (c0d9fd44)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (c0db7790)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (c0dcc4c8)
Location: include/net/sock.h:2499
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
In net/ipv4/xfrm4_output.c (c0de17f0)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (c0dfc14c)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (c0e03fc0)
Location: include/net/sock.h:2499
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (c0e1ada4)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (c0e22498)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (c0e24be0)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c0e289cc)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e31c28)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (c0e3c7fc)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (c0e40c8c)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_local_dontfrag
```
```
In net/ipv6/syncookies.c (c0e4d810)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (c0e4fa60)
Location: include/net/sock.h:2499
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
In kernel/bpf/cgroup.c (c00000000033b0dc)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (c000000000c76c80)
Location: include/net/sock.h:2499
Inline: True
```
```
In net/core/sock.c (c000000000c80134)
Location: include/net/sock.h:2499
Inline: True
```
```
In net/core/dev.c (c000000000ca482c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (c000000000cd94c8)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (c000000000d059b4)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_output.c (c000000000d65c4c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e470)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (c000000000d7dd64)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (c000000000d857f4)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (c000000000d90888)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (c000000000d9653c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d0e4)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9ec50)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (c000000000da0714)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (c000000000dc115c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (c000000000ddb350)
Location: include/net/sock.h:2499
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
In net/ipv4/xfrm4_output.c (c000000000df7da8)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (c000000000e1b8a8)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (c000000000e24800)
Location: include/net/sock.h:2499
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (c000000000e42068)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4c0f4)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (c000000000e4e7f8)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c000000000e54c0c)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c000000000e5faf0)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (c000000000e6d500)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (c000000000e71ee4)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (c000000000e82c00)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (c000000000e85e5c)
Location: include/net/sock.h:2499
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
In kernel/bpf/cgroup.c (ffffffe0001c1a58)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffe00073a0a8)
Location: include/net/sock.h:2499
Inline: True
```
```
In net/core/sock.c (ffffffe00073ec1a)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffe000754b60)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffe0007757f4)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffe0007924e0)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_output.c (ffffffe0007ca3a6)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf5ca)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffe0007d9428)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffe0007de4f2)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffe0007e63e4)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea1ea)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eea9c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efe08)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffe0007f0ea0)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffe000805a92)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffe000816a60)
Location: include/net/sock.h:2499
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
In net/ipv4/xfrm4_output.c (ffffffe000828306)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (ffffffe000841114)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffe0008472ba)
Location: include/net/sock.h:2499
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffe00085a7fc)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe000860a14)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffe000862168)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffe000865d5c)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffe00086dda2)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffe000876f8c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffe00087a110)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffe0008852d8)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffe0008863e0)
Location: include/net/sock.h:2499
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
In kernel/bpf/cgroup.c (ffffffff811fdf4e)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff818ad072)
Location: include/net/sock.h:2499
Inline: True
```
```
In net/core/sock.c (ffffffff818b386c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffff818cbfeb)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff818f2115)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff819105bd)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_output.c (ffffffff81951c4b)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff8195822d)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff8196354e)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff81968a1d)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff81971ca7)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff819763a9)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b1d8)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197ca01)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff8197da4d)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81994d1f)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff819a6e3e)
Location: include/net/sock.h:2499
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
In net/ipv4/xfrm4_output.c (ffffffff819bb107)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (ffffffff819d4425)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff819daf96)
Location: include/net/sock.h:2499
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff819f0875)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f7b9e)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff819fa333)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819ff0f6)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a0755c)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81a10f17)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a146b3)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff81a20380)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a225a4)
Location: include/net/sock.h:2499
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
In kernel/bpf/cgroup.c (ffffffff811f0c9e)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff81866fc2)
Location: include/net/sock.h:2499
Inline: True
```
```
In net/core/sock.c (ffffffff8186d7bc)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffff81885f2b)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff818abf45)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff818ca37d)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_output.c (ffffffff8190b73b)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911d1d)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff8191d03e)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff8192250d)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff8192b777)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8192fe69)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934c98)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819364c1)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff8193750d)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff8194e7df)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff819608fe)
Location: include/net/sock.h:2499
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
In net/ipv4/xfrm4_output.c (ffffffff81977ef7)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (ffffffff819911e5)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81997d56)
Location: include/net/sock.h:2499
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff819ad635)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b495e)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff819b70f3)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bbeb6)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c431c)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff819cdcd7)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff819d1473)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff819dd140)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff819df364)
Location: include/net/sock.h:2499
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
In kernel/bpf/cgroup.c (ffffffff811fbd1e)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff818fe072)
Location: include/net/sock.h:2499
Inline: True
```
```
In net/core/sock.c (ffffffff8190486c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffff8191cfeb)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81943145)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff819615ed)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999d4c)
Location: include/net/sock.h:2499
Inline: True
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199c0d9)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:__build_packet_message
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a445b)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst
```
```
In net/ipv4/ip_output.c (ffffffff819bc41b)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c29fd)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff819cdd1e)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819d31ed)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff819dc477)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0b79)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e59a8)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e71d1)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819e821d)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff819ff5bf)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff81a116de)
Location: include/net/sock.h:2499
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
In net/ipv4/netfilter/nf_defrag_ipv4.c (ffffffff81a20bb8)
Location: include/net/sock.h:2499
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25b87)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (ffffffff81a3eea5)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a45a16)
Location: include/net/sock.h:2499
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81a5b2f5)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6261e)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81a64db3)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a69b76)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a71fdc)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81a7b997)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a7f133)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff81a8ae00)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a8d024)
Location: include/net/sock.h:2499
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
In kernel/bpf/cgroup.c (ffffffff8120a8fe)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff8191f102)
Location: include/net/sock.h:2499
Inline: True
```
```
In net/core/sock.c (ffffffff8192590c)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/dev.c (ffffffff8193e4d1)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/filter.c (ffffffff81964a35)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_tcp_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:bpf_sock_ops_cb_flags_set
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_getsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_socket_uid
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_sk_fullsock
```
```
In net/core/net-traces.c (ffffffff8198385d)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
```
```
In net/ipv4/ip_output.c (ffffffff819c5d2b)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc3fd)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ipv4_pktinfo_prepare
```
```
In net/ipv4/tcp.c (ffffffff819d78ae)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff819dcd93)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff819e60f7)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea839)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef668)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0ea1)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff819f1f4d)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81a096bf)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_listen
```
```
In net/ipv4/ping.c (ffffffff81a1c04e)
Location: include/net/sock.h:2499
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
In net/ipv4/xfrm4_output.c (ffffffff81a31027)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/af_inet6.c (ffffffff81a4a965)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a516e6)
Location: include/net/sock.h:2499
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
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81a675d5)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:ip6_route_output_flags_noref
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6eb1e)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/ndisc.c (ffffffff81a712e3)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_net_init
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a76186)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a7e60c)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/ping.c (ffffffff81a881e7)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a8b9f3)
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
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
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/syncookies.c (ffffffff81a97a60)
Location: include/net/sock.h:2499
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81a99ce4)
Location: include/net/sock.h:2499
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
<b>Regular</b>
<ul>
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
