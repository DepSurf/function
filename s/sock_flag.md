# Function: <code>sock_flag</code>

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
In drivers/net/tun.c (ffffffff815eeae5)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/socket.c (ffffffff816fccac)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff817010d1)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_queue_rcv_skb
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sk_receive_skb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_get_timestampns
```
```
In net/core/skbuff.c (ffffffff817061f2)
Location: include/net/sock.h:761
Inline: True
```
```
In net/core/datagram.c (ffffffff8170c91a)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/filter.c (ffffffff81730b1d)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_attach_bpf
```
```
In net/compat.c (ffffffff8173e418)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/compat.c:compat_sock_get_timestamp
  - net/compat.c:compat_sock_get_timestampns
```
```
In net/netlink/af_netlink.c (ffffffff8174a84f)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff81754cd8)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8175e68f)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761bfb)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8176423d)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff81765ab3)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8176aa35)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_timer.c (ffffffff81779a12)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_set_keepalive
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c45b)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177f01f)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff81783c9c)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81784e6e)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81787738)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/af_inet.c (ffffffff81793160)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff817a3456)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff817ab727)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/unix/af_unix.c (ffffffff817bdcac)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff817c616c)
Location: include/net/sock.h:761
Inline: True
```
```
In net/ipv6/udp.c (ffffffff817e4365)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f02de)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff817f4ea4)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81802d2d)
Location: include/net/sock.h:761
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sock_destruct
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/socket.c (ffffffff81764bea)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81767c51)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8176cbf3)
Location: include/net/sock.h:763
Inline: True
```
```
In net/core/datagram.c (ffffffff8177536a)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81775bb7)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff8179e445)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/compat.c (ffffffff817ab1d8)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
```
In net/netlink/af_netlink.c (ffffffff817ba58f)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff817c2fc2)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff817ca8f4)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cdef8)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0c5c)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff817d702a)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff817e0d41)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff817e6be2)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_set_keepalive
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ec19d)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec4d1)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff817f1253)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff817f2468)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f7238)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81800920)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff818104b6)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81819226)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/unix/af_unix.c (ffffffff8182b156)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81833174)
Location: include/net/sock.h:763
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81852745)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860d16)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81863f54)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81874e81)
Location: include/net/sock.h:763
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
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
In net/socket.c (ffffffff81791c6a)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81794c71)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81799dc3)
Location: include/net/sock.h:784
Inline: True
```
```
In net/core/datagram.c (ffffffff817a265a)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff817a2d90)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff817ccea5)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
```
```
In net/compat.c (ffffffff817da7f8)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
```
In net/netlink/af_netlink.c (ffffffff817e9f30)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff817f0acc)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff817fa568)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdc58)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800ae5)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff8180704a)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81811143)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81817322)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_set_keepalive
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181a537)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181cdbb)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff818222e7)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81823245)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81824d57)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81831860)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff818419b6)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff8184aa9a)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/unix/af_unix.c (ffffffff8185cb86)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81864cec)
Location: include/net/sock.h:784
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81890e3d)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81896604)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff818a9341)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
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
In net/socket.c (ffffffff817af24a)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff817b2e5e)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff817b9324)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
```
```
In net/core/datagram.c (ffffffff817c0168)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff817c0e20)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff817ec3d5)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
```
```
In net/compat.c (ffffffff817f9d2a)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
```
In net/netlink/af_netlink.c (ffffffff81809bfe)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff81810f19)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8181a972)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e090)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818206d5)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff81822899)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff818311e3)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff818376c2)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183acc3)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d5c2)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff81842f57)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818435f9)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81847223)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81852df0)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81863095)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff8186e48f)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/unix/af_unix.c (ffffffff81881304)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81888310)
Location: include/net/sock.h:798
Inline: True
```
```
In net/ipv6/udp.c (ffffffff818a7ff2)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff818abbdc)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b745b)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff818bcb84)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff818cfdd1)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
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
In kernel/bpf/sockmap.c (ffffffff811b0e2d)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In net/socket.c (ffffffff8182738a)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8182b14e)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81831c62)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/datagram.c (ffffffff81839b7e)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff8183a833)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff818681b5)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
```
```
In net/compat.c (ffffffff8187763a)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
```
In net/netlink/af_netlink.c (ffffffff81888b54)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff818904f9)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81899952)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189cfa0)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189f6a5)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff818a1999)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff818b062b)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff818b6de6)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818ba8f3)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bccb5)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff818c28bd)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818c2fd9)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818c6c83)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff818d2c10)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff818e31c5)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff818eee29)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/unix/af_unix.c (ffffffff8190249a)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff8190a6f2)
Location: include/net/sock.h:798
Inline: True
```
```
In net/ipv6/udp.c (ffffffff8192aaa2)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff8192e79c)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193a29b)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff8193fca4)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81954ca1)
Location: include/net/sock.h:798
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
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
In kernel/bpf/sockmap.c (ffffffff811cc7fd)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
```
```
In net/socket.c (ffffffff818707fa)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff818751ce)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8187e20c)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff818842c9)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81884fac)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff818b8315)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
```
```
In net/compat.c (ffffffff818c8d38)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
```
In net/netlink/af_netlink.c (ffffffff818dc61a)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff818e3c89)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff818eddbc)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f146a)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f40cf)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff818fb296)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81905eca)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c663)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190f3ca)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912b15)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff8191852b)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81918ae6)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8191d333)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819291c0)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81939bd6)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81945757)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/unix/af_unix.c (ffffffff81959df4)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81961af1)
Location: include/net/sock.h:805
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81982dbb)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81987678)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993102)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81998ae4)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff819b0fd4)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffffffff819cc065)
Location: include/net/sock.h:805
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
In kernel/bpf/reuseport_array.c (ffffffff811e28d9)
Location: include/net/sock.h:833
Inline: True
```
```
In net/socket.c (ffffffff8189130a)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81895a9b)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8189edcc)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff818a473b)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff818a55ae)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff818ded75)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff818e5f0e)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff81908ffa)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff81910b69)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81919275)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191efc7)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921bdf)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff819291e6)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff8193406b)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff8193a98d)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f5d6)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819412df)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff81946cab)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819472b3)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8194b8e3)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81958460)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81969863)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81975af7)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff81977ee2)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8198ef49)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (ffffffff81995c76)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff819b9683)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819be602)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c947d)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819cf431)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff819e63c4)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffffffff81a04735)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct
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
In kernel/bpf/reuseport_array.c (ffffffff811f9a54)
Location: include/net/sock.h:836
Inline: True
```
```
In net/socket.c (ffffffff818daffa)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff818dffbd)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818e960c)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff818efeb7)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff818f08de)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff8192ccb5)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff81935afc)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff8196a35e)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff81972db0)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8197b5a9)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981906)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819845b5)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff8198c103)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81997db8)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_timer.c (ffffffff8199ed3d)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a3bec)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a58a3)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff819ab32c)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819ab933)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819affbd)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819bcf80)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff819d04b0)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff819df661)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e190b)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819fa6c3)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (ffffffff81a019bb)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff81a27f61)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a2c772)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a3e17e)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a55e23)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffffffff81a73c55)
Location: include/net/sock.h:836
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct
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
In kernel/bpf/reuseport_array.c (ffffffff81206b24)
Location: include/net/sock.h:841
Inline: True
```
```
In net/socket.c (ffffffff8190d14a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8191216d)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8191b76c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff81921eda)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81922830)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff8195efb5)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff8196890c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff819a0dce)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff819a9720)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819b24ae)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b8146)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bad65)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff819c2a53)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff819ce948)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_timer.c (ffffffff819d57dd)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da8ee)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc663)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff819e1ffc)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819e2603)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819e6c5a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819f3b90)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81a07000)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81a166a5)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a1891b)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a31346)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (ffffffff81a3857c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff81a5e9ca)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a63b93)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a74dee)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a8d303)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffffffff81aaa355)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct
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
In kernel/bpf/reuseport_array.c (ffffffff8122f0e8)
Location: include/net/sock.h:883
Inline: True
```
```
In net/socket.c (ffffffff819dfe1b)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff819e4c7d)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wait_for_wmem
  - net/core/sock.c:sock_pfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:__sk_free
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/skbuff.c (ffffffff819eb778)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff819f511a)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff819f63d2)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff81a2ba9d)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff81a3d420)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_skb_redirect
```
```
In net/core/sock_map.c (ffffffff81a4effc)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a7a5aa)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff81a963d3)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:build_sk_flow_key
```
```
In net/ipv4/ip_output.c (ffffffff81a9bafe)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2a66)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5625)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff81aa94df)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81abaab7)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_reset
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac29af)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8b65)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9733)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff81acf2fc)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ad04dc)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ad7988)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81ae3694)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81af7600)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81b07672)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b08703)
Location: include/net/sock.h:883
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b25302)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e410)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff81b5af8d)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b5c62a)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a7ac)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81b6f03e)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81b8991c)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffffffff81ba70f5)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mptcp/protocol.c (ffffffff81babcfe)
Location: include/net/sock.h:883
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:mptcp_wait_data
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
In kernel/bpf/reuseport_array.c (ffffffff81237608)
Location: include/net/sock.h:898
Inline: True
```
```
In net/socket.c (ffffffff819df5db)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff819e453d)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wait_for_wmem
  - net/core/sock.c:sock_pfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:__sk_free
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/skbuff.c (ffffffff819eb498)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff819f4b4a)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff819f6024)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff81a304e3)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff81a3f1b1)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
```
```
In net/core/sock_map.c (ffffffff81a54bca)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a83415)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff81aa0473)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:build_sk_flow_key
```
```
In net/ipv4/ip_output.c (ffffffff81aa595e)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacd76)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafc35)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff81ab37ff)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81ac5efa)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_reset
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace3df)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4b05)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5673)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff81adb301)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81adc4ec)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ae3fd8)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81af024b)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81b044e0)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81b15a71)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b168a3)
Location: include/net/sock.h:898
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b33e72)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ce60)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff81b69753)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b6ae6a)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b791fb)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81b7db6e)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81b99431)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:fanout_set_data
  - net/packet/af_packet.c:fanout_set_data
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffffffff81bb6dc0)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mptcp/protocol.c (ffffffff81bbf406)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_check_fastclose
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:mptcp_wait_data
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
In kernel/bpf/reuseport_array.c (ffffffff8123be28)
Location: include/net/sock.h:898
Inline: True
```
```
In net/socket.c (ffffffff819c609b)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff819ca5f6)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_pfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:__sk_free
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/skbuff.c (ffffffff819d19a8)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff819dacda)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff819dc090)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff81a17449)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff81a4e37c)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_wait_data
  - net/core/skmsg.c:sk_msg_wait_data
```
```
In net/core/sock_map.c (ffffffff81a51086)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a6c4e5)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff81a8b3b3)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81a9109e)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a97fdf)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9af45)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff81a9ecdf)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81ab110c)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_reset
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab956f)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfbb2)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac06e3)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff81ac6362)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ac745b)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ac9eb8)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81adbab0)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81aef507)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81b0387f)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/unix/af_unix.c (ffffffff81b21822)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a2c0)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff81b57a51)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b5917c)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67d35)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81b6c777)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81b884d1)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffffffff81ba5ce0)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mptcp/protocol.c (ffffffff81bb01cf)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:mptcp_wait_data
```
```
In net/mptcp/sockopt.c (ffffffff81bbbfb1)
Location: include/net/sock.h:898
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
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
In kernel/bpf/reuseport_array.c (ffffffff812767b8)
Location: include/net/sock.h:910
Inline: True
```
```
In net/socket.c (ffffffff81a74ceb)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81a79b96)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_pfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:__sk_free
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/skbuff.c (ffffffff81a815a6)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:msg_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff81a8b35a)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81a8c2d0)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff81acdee7)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff81b0703e)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81b093d3)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81b25b43)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f322)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81b462f3)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81b4be2e)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b5346f)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b563b5)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff81b5ac7f)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81b6df6a)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_reset
```
```
In net/ipv4/tcp_timer.c (ffffffff81b7699f)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d739)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e095)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff81b84b72)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81b85c7b)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81b88748)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81b9aced)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81bb0a87)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81bc5b0f)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc8044)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc8873)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff81be6b72)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/unix/unix_bpf.c (ffffffff81beb613)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_msg_wait_data
  - net/unix/unix_bpf.c:unix_msg_wait_data
```
```
In net/ipv6/ip6_output.c (ffffffff81befe9b)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff81c1f047)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81c20758)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f991)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81c34666)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81c545e1)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffffffff81c74350)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mptcp/protocol.c (ffffffff81c7cbf2)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
```
```
In net/mptcp/sockopt.c (ffffffff81c8bb51)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
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
In kernel/bpf/reuseport_array.c (ffffffff812c623c)
Location: include/net/sock.h:950
Inline: True
```
```
In net/socket.c (ffffffff81be79ab)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81bec936)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:__sk_free
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/skbuff.c (ffffffff81bf5233)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff81c0060b)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81c01b6e)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff81c4bc5c)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff81c8bc0a)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81c8f4a3)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81cae6ef)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/netfilter/nf_queue.c (ffffffff81ccba84)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81cd3137)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81cd955e)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdfb91)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce44f2)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff81cef020)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_sock_set_keepidle_locked
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81cfd3ce)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_reset
```
```
In net/ipv4/tcp_timer.c (ffffffff81d061bf)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d6dd)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0dfd4)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff81d15411)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81d15f36)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81d19799)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81d2c753)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81d4401d)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81d5adf1)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5d64e)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5e0aa)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81d7d556)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/unix/unix_bpf.c (ffffffff81d83a83)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81d87f30)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff81dbb8ca)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81dbd4e0)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcce08)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81dd1fae)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81df2ca1)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/xdp/xsk.c (ffffffff81e17394)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mptcp/protocol.c (ffffffff81e22306)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
```
```
In net/mptcp/subflow.c (ffffffff81e26f13)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
```
In net/mptcp/sockopt.c (ffffffff81e331c1)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
```
```
In net/mctp/af_mctp.c (ffffffff81e37051)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
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
In kernel/bpf/reuseport_array.c (ffffffff8132b9ac)
Location: include/net/sock.h:988
Inline: True
```
```
In net/socket.c (ffffffff81d93e6b)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_wifi_status
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81d9b3c6)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/skbuff.c (ffffffff81da3753)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff81dafe0b)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81db0f2e)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff81dfbc8c)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff81e47f9a)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81e4a74f)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81e6bd2d)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b8d4)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81e90a10)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81e99cbd)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9ff40)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea74a2)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff81eb2202)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_sock_set_keepidle_locked
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff81ec1f8e)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_reset
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb52d)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed3099)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3ac4)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff81edbc01)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81edce60)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ee0b09)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81ef50f3)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81f0d4ed)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81f25261)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27d4e)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81f285ff)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff81f4ad66)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/unix/unix_bpf.c (ffffffff81f51283)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81f55ccc)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff81f8ba09)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81f8da1f)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9df16)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff81fa340e)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81fc7091)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:fanout_set_data
  - net/packet/af_packet.c:fanout_set_data
```
```
In net/xdp/xsk.c (ffffffff81fede16)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mptcp/protocol.c (ffffffff81ffa4d9)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_reset_timeout
  - net/mptcp/protocol.c:mptcp_reset_timeout
```
```
In net/mptcp/subflow.c (ffffffff81fff927)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:subflow_check_data_avail
```
```
In net/mptcp/sockopt.c (ffffffff8200c8c1)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
```
```
In net/mctp/af_mctp.c (ffffffff82010a71)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
```
```
In net/mctp/route.c (ffffffff820132d7)
Location: include/net/sock.h:988
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_key_add
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
In kernel/bpf/reuseport_array.c (ffffffff8135bb1c)
Location: include/net/sock.h:990
Inline: True
```
```
In net/socket.c (ffffffff81e01a0b)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_wifi_status
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81e09796)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/skbuff.c (ffffffff81e12348)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff81e2007b)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81e2141e)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff81e6cb6d)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:__bpf_sk_lookup
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff81ea310f)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81ea5e57)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81ec7d8d)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/netfilter/nf_queue.c (ffffffff81ee991e)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81eef1a9)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81ef9fb0)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe790)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05c42)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff81f108c2)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_sock_set_keepidle_locked
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81f204f7)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_reset
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a07d)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31e8a)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32aa4)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff81f3acd1)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81f3c0b0)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81f40185)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81f549d3)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81f6d14d)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81f84e09)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87903)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff81f8816f)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff81faaa1d)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/unix/unix_bpf.c (ffffffff81fb0be3)
Location: include/net/sock.h:990
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb56a4)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff81fec2ac)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81fee1fb)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffea2e)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/datagram.c (ffffffff82003cba)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff82027dae)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:fanout_set_data
  - net/packet/af_packet.c:fanout_set_data
```
```
In net/xdp/xsk.c (ffffffff82069f76)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mptcp/protocol.c (ffffffff82076c07)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_reset_timeout
  - net/mptcp/protocol.c:mptcp_reset_timeout
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff8207b9f7)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_error_report
  - net/mptcp/subflow.c:subflow_check_data_avail
```
```
In net/mptcp/sockopt.c (ffffffff82089201)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
```
```
In net/mctp/af_mctp.c (ffffffff8208d23d)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
```
```
In net/mctp/route.c (ffffffff820900f7)
Location: include/net/sock.h:990
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_key_add
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
In kernel/bpf/reuseport_array.c (ffffffff813847ac)
Location: include/net/sock.h:961
Inline: True
```
```
In net/socket.c (ffffffff81ebe3d5)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_wifi_status
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81ec618e)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/skbuff.c (ffffffff81ecf508)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__msg_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff81eddf5b)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81edf1b6)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff81f2b59d)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:__bpf_sk_lookup
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff81f6542f)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81f68917)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81f8b19f)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/netfilter/nf_queue.c (ffffffff81fad6bd)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81fb330f)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81fbdef1)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc29b7)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9da2)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff81fd4aa2)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_sock_set_keepidle_locked
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81fe4b74)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_reset
```
```
In net/ipv4/tcp_timer.c (ffffffff81feebed)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff6558)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8af4)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff82000dc1)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff820021d4)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff820079f5)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8201ac26)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff820338c4)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff8204b55c)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204efa0)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
```
```
In net/ipv4/udp_bpf.c (ffffffff8204f88f)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/af_unix.c (ffffffff82077e0d)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/unix/unix_bpf.c (ffffffff8207e283)
Location: include/net/sock.h:961
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff82082d92)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff820b6c7d)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff820bbdcb)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c943c)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:__inet6_lookup_skb
```
```
In net/ipv6/datagram.c (ffffffff820d2a71)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff820f760e)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:fanout_set_data
  - net/packet/af_packet.c:fanout_set_data
```
```
In net/xdp/xsk.c (ffffffff8213d3d6)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mptcp/protocol.c (ffffffff8214b67b)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_error_report
```
```
In net/mptcp/subflow.c (ffffffff8214fbdb)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
```
In net/mptcp/ctrl.c (ffffffff821561e5)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/mptcp/ctrl.c:mptcp_close_timeout
```
```
In net/mptcp/sockopt.c (ffffffff8215ec91)
Location: include/net/sock.h:961
Inline: True
```
```
In net/mctp/af_mctp.c (ffffffff821636fe)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
```
```
In net/mctp/route.c (ffffffff82166637)
Location: include/net/sock.h:961
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_key_add
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
In kernel/bpf/reuseport_array.c (ffff800010290318)
Location: include/net/sock.h:841
Inline: True
```
```
In net/socket.c (ffff800010ba20ac)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffff800010ba9be4)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb5c9c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffff800010bbc590)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffff800010bbd598)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffff800010c023f0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffff800010c0f424)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffff800010c4f4dc)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffff800010c5912c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffff800010c62020)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffff800010c694f4)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6ca54)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffff800010c757a4)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffff800010c81350)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_timer.c (ffff800010c8898c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8dcb4)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8fb34)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffff800010c95cc8)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffff800010c96474)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffff800010c9d170)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffff800010caa1c8)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffff800010cbff68)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffff800010cd236c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd4408)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffff800010cf1c88)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (ffff800010cf8afc)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffff800010d25ec0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d29c40)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffff800010d3d838)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffff800010d5af24)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffff800010d7ded8)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct
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
In kernel/bpf/reuseport_array.c (c04bf940)
Location: include/net/sock.h:841
Inline: True
```
```
In net/socket.c (c0cc483c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (c0cc82a8)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (c0cd2ca0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (c0cd88bc)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (c0cd95c4)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (c0d1b944)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (c0d26944)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (c0d5f640)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (c0d68e74)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (c0d71a54)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (c0d786cc)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (c0d7b738)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (c0d7ed14)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (c0d9054c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_timer.c (c0d9776c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c0d9c9c0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (c0d9e720)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (c0da442c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da570c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (c0daa6f0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (c0db66ec)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (c0dcc3f0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (c0ddc218)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (c0dde5d4)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (c0df7af0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (c0e00c68)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (c0e2a2f0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2d9e0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (c0e409f8)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (c0e57c00)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (c0e78a50)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct
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
In kernel/bpf/reuseport_array.c (c00000000033d178)
Location: include/net/sock.h:841
Inline: True
```
```
In net/socket.c (c000000000c76db4)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (c000000000c7f330)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sk_backlog_rcv
```
```
In net/core/skbuff.c (c000000000c867ac)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (c000000000c9464c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (c000000000c966f0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (c000000000ceb720)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (c000000000cfa010)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (c000000000d4dd20)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (c000000000d5aff4)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (c000000000d66648)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e134)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (c000000000d7237c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (c000000000d76d94)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (c000000000d8c2f4)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_timer.c (c000000000d95458)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9b550)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e5f0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (c000000000da74c0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c000000000da7d6c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c000000000dac2d4)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (c000000000dbf5d4)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (c000000000ddb2c0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (c000000000df07ac)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (c000000000df2454)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (c000000000e158b0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (c000000000e21ce0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (c000000000e53c24)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c000000000e5aa58)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (c000000000e71c50)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (c000000000e92414)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (c000000000ebda60)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct
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
In kernel/bpf/reuseport_array.c (ffffffe0001c2e96)
Location: include/net/sock.h:841
Inline: True
```
```
In net/socket.c (ffffffe00073a16a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffe00073d16c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffe000745ba4)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffffffe00074a6fe)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffe00074b9f0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffe0007817e8)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffe00078afda)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffe0007bb0e6)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffe0007c3020)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffe0007caa60)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf3d0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d233e)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffe0007d4ada)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffe0007e32a8)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e96d6)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee182)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef9a8)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffe0007f5122)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffe0007f5682)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffe0007f91f2)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffe0008049aa)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffe0008169f8)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffe0008236c0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffe000825382)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffe00083da22)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (ffffffe00084481a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffe000865240)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffe00086a468)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffe000879f50)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffe0008911ac)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffffffe0008ab6ea)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct
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
In kernel/bpf/reuseport_array.c (ffffffff811ff144)
Location: include/net/sock.h:841
Inline: True
```
```
In net/socket.c (ffffffff818ad14a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff818b216d)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818bb76c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff818c1eda)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff818c2830)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff818fef85)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff819088dc)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff81940c3e)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff81949590)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8195231e)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81957fb6)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195abd5)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff819628c3)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff8196e7b8)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_timer.c (ffffffff8197564d)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a75e)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c4d3)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff81981e6c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81982473)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81986aca)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81993930)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff819a6da0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff819b5d35)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7fab)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819d09d6)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (ffffffff819d7c0c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff819fe05a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a03223)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a1447e)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a2c993)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffffffff81a496e5)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct
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
In kernel/bpf/reuseport_array.c (ffffffff811f1e94)
Location: include/net/sock.h:841
Inline: True
```
```
In net/socket.c (ffffffff8186709a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8186c0bd)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818756ac)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff8187be1a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff8187c770)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff818b8db5)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff818c26ec)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff818fa72e)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff81903080)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8190be0e)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911aa6)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819146c5)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff8191c3b3)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff819282a8)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f10d)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193421e)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81935f93)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff8193b92c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8193bf33)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8194058a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8194d3f0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81960860)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81972b25)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974d9b)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8198d796)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (ffffffff819949cc)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff819bae1a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819bffe3)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff819d123e)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff819e9b83)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffffffff81a062d5)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct
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
In kernel/bpf/reuseport_array.c (ffffffff811fcf14)
Location: include/net/sock.h:841
Inline: True
```
```
In net/socket.c (ffffffff818fe14a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8190316d)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8190c76c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff81912eda)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff81913830)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff8194ffb5)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff8195990c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff81991dce)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff819b3d60)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819bcaee)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c2786)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c53a5)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff819cd093)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff819d8f88)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_timer.c (ffffffff819dfe1d)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4f2e)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6ca3)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff819ec63c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819ecc43)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819f129a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819fe1d0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81a11640)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81a205d5)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22a2b)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a3b456)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (ffffffff81a4268c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff81a68ada)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a6dca3)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a7eefe)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a98543)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffffffff81ab5595)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct
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
In kernel/bpf/reuseport_array.c (ffffffff8120bbc4)
Location: include/net/sock.h:841
Inline: True
```
```
In net/socket.c (ffffffff8191f1da)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8192414d)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192d8ac)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffffffff8193405a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffffffff819349b3)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff81971985)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/filter.c:sk_detach_filter
  - net/core/filter.c:bpf_get_listener_sock
  - net/core/filter.c:bpf_sk_release
  - net/core/filter.c:sk_lookup
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/filter.c:__get_filter
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/skmsg.c (ffffffff8197bb2c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/netlink/af_netlink.c (ffffffff819b48be)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/ipv4/route.c (ffffffff819bd44f)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819c63fe)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc186)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cee7a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffffffff819d6c23)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_recv_timestamp
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_peek_len
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_tx_timestamp
```
```
In net/ipv4/tcp_input.c (ffffffff819e2bf3)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9add)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ee28c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0973)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/datagram.c (ffffffff819f6526)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819f6b33)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819faf7a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81a08560)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_release
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/ping.c (ffffffff81a1bfb0)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81a2bad5)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2de1e)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a460d6)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
```
In net/ipv6/ip6_output.c (ffffffff81a4e31c)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/udp.c (ffffffff81a750c5)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a7a2c3)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a8b7be)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81aa1b3a)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_sock_destruct
```
```
In net/xdp/xsk.c (ffffffff81ac1b85)
Location: include/net/sock.h:841
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct
  - net/xdp/xsk.c:xsk_notifier
```
</details>
</li>
</ul>

## Differences
