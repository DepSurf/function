# Function: <code>lock_sock</code>

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
In security/selinux/netlabel.c (ffffffff8135da7e)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
```
In net/socket.c (ffffffff816fb9b8)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81702401)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/skbuff.c (ffffffff8170c0d7)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_socket_splice
```
```
In net/core/stream.c (ffffffff8170defc)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/filter.c (ffffffff81732e85)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/netlink/af_netlink.c (ffffffff8174cbbf)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff8175fd27)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764e67)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff817662a0)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/datagram.c (ffffffff817840b7)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff817847c6)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81786eeb)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendpage
```
```
In net/ipv4/devinet.c (ffffffff8178fa53)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (ffffffff81792f68)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_autobind
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv4/ping.c (ffffffff817a2a86)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/af_inet6.c (ffffffff817c2bf9)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff817ca0a5)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817dc4eb)
Location: include/net/sock.h:1479
Inline: True
```
```
In net/ipv6/udp.c (ffffffff817e213c)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_destroy_sock
```
```
In net/ipv6/raw.c (ffffffff817e51ce)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/ping.c (ffffffff817f27fc)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff817f4557)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffff81804d48)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In security/selinux/netlabel.c (ffffffff81393b85)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff8164fecd)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff81762418)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8176964c)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/skbuff.c (ffffffff81773b77)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_socket_splice
```
```
In net/core/stream.c (ffffffff81775b48)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff8179e898)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/netlink/af_netlink.c (ffffffff817b8f8f)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cbfc7)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d1576)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff817d6d36)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff817f1647)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff817f1d76)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f41ba)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff817fd143)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (ffffffff81800831)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81810a57)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff8182fc58)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff818371d5)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184a393)
Location: include/net/sock.h:1396
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81851056)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81853716)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff8186155a)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff818637d5)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffff81875d1f)
Location: include/net/sock.h:1396
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In security/selinux/netlabel.c (ffffffff813aa7a5)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff816815c3)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff8178f448)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81796557)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff817a2d21)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff817cd268)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/netlink/af_netlink.c (ffffffff817e8a57)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fbcb7)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81801441)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81806d56)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff81822227)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818227c2)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81824b82)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff8182e0a3)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (ffffffff81831771)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81841f64)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff818616d8)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81868cd5)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187c237)
Location: include/net/sock.h:1452
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81882ea6)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81885426)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff818934a7)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff818960f7)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffff818aa118)
Location: include/net/sock.h:1452
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
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
In security/selinux/netlabel.c (ffffffff813c118a)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff81696f44)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff817ad3c8)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff817b4717)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff817c0f32)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff817ec6b8)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/netlink/af_netlink.c (ffffffff81808085)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181c067)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81821913)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81827366)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff81842e97)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81843402)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818458d2)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff8184fd2c)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (ffffffff81852d21)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81863829)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81885e40)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff8188d3a5)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a1c2e)
Location: include/net/sock.h:1455
Inline: True
```
```
In net/ipv6/udp.c (ffffffff818a88e6)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff818ab806)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff818b9a92)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff818bc6a7)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffff818d0c98)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
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
In kernel/bpf/sockmap.c (ffffffff811b0c16)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_tx_work
```
```
In security/selinux/netlabel.c (ffffffff813e739a)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff81701e5e)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff81825358)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8182c977)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/skbuff.c (ffffffff81830a0c)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_send_sock
```
```
In net/core/stream.c (ffffffff8183a950)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff81868898)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/netlink/af_netlink.c (ffffffff81886ec5)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189afb7)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a0697)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818a6166)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff818c27f7)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818c2de2)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818c5342)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff818cf95c)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (ffffffff818d2b31)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff818e396c)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81906ff3)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff8190e415)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819245d5)
Location: include/net/sock.h:1459
Inline: True
```
```
In net/ipv6/udp.c (ffffffff8192b396)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff8192e3c6)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff8193ca18)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff8193f7c7)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffff81955bb8)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
```
```
In net/strparser/strparser.c (ffffffff8195ad36)
Location: include/net/sock.h:1459
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
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
In kernel/bpf/sockmap.c (ffffffff811cde0a)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:sock_hash_update_elem
  - kernel/bpf/sockmap.c:sock_map_update_elem
  - kernel/bpf/sockmap.c:smap_tx_work
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:bpf_tcp_close
```
```
In security/selinux/netlabel.c (ffffffff814182f5)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff81740bee)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff8186f308)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81877847)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/skbuff.c (ffffffff8187aec5)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_send_sock
```
```
In net/core/stream.c (ffffffff818850b1)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff818b86e5)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/netlink/af_netlink.c (ffffffff818db012)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff818ef503)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f5467)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818fb1c5)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff81918445)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819188c5)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8191ad05)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff8192566c)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (ffffffff819290e1)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff8193a1dc)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff8195eb50)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81965575)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197ca37)
Location: include/net/sock.h:1472
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819845f5)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81987065)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff81995a84)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff819985e5)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffff819b3375)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff819b43e5)
Location: include/net/sock.h:1472
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
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
In security/selinux/netlabel.c (ffffffff81434885)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff81764d94)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff8188f7c8)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81898967)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff818a56bb)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff818df2b5)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (ffffffff818e6355)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff818f2ac6)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/netlink/af_netlink.c (ffffffff81907912)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191cceb)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922da7)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81929115)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff81946bc5)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81947095)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819494c5)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff8195447c)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (ffffffff81958301)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff8196a127)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff8197772e)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff819936c2)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff8199a9f5)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b2569)
Location: include/net/sock.h:1510
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bab25)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff819bd985)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff819cc398)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff819cef55)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffff819ea385)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff819eb415)
Location: include/net/sock.h:1510
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
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
In kernel/bpf/cgroup.c (ffffffff811f82f9)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff81462335)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff817a2bb3)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff818d982b)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818e2f03)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff818f09f8)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff8192d815)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (ffffffff81935cf5)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81944c14)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/netlink/af_netlink.c (ffffffff81968e5e)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197f08f)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8198575e)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff8198c025)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff819ab245)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819ab715)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819adb15)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff819b92cd)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (ffffffff819bce11)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff819d0caf)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e124e)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff819ff15d)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81a06994)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a20ec2)
Location: include/net/sock.h:1520
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a289e5)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a2c465)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff81a3ae8c)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a3dc65)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffff81a59279)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff81a5a5e5)
Location: include/net/sock.h:1520
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
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
In kernel/bpf/cgroup.c (ffffffff81204fd9)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff8147c0e5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff817c4d43)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff8190b80b)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819150e3)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff8192294e)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff8195fb15)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (ffffffff81968a15)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff819792f8)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff8199f8fe)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b55cf)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bc453)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819c2975)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff819e1f15)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819e23e5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819e4825)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff819effcd)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (ffffffff819f3a21)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81a07809)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a1860e)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81a35d5d)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81a3d504)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a57932)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a5f4d5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a62fa5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff81a71b0c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a748d5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffff81a8f389)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff81a91235)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
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
In kernel/bpf/cgroup.c (ffffffff8122ec52)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff814d17c5)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff8188b3bc)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach_filter
  - drivers/net/tun.c:tun_attach_filter
```
```
In net/socket.c (ffffffff819dd9fb)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819e8453)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
```
```
In net/core/stream.c (ffffffff819f64f0)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff81a33035)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (ffffffff81a3bf95)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81a4eb15)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff81a77cbb)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa0685)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_setsockopt
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6fda)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
```
```
In net/ipv4/tcp.c (ffffffff81aa79c9)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff81acf795)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81acfbe5)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ad22d5)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff81adda85)
Location: include/net/sock.h:1579
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81ae1ce1)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81af705a)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b09346)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/xfrm/espintcp.c (ffffffff81b22df5)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b29dae)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81b32af4)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b505bd)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_setsockopt
```
```
In net/ipv6/udp.c (ffffffff81b58435)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b5ba45)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff81b6b3ff)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6eb4e)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
```
In net/packet/af_packet.c (ffffffff81b8a6a1)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff81b8c645)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
```
```
In net/mptcp/protocol.c (ffffffff81baca54)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_shutdown
  - net/mptcp/protocol.c:mptcp_shutdown
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_getsockopt
  - net/mptcp/protocol.c:mptcp_setsockopt
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
```
In net/mptcp/subflow.c (ffffffff81bafba1)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
```
In net/mptcp/pm.c (ffffffff81bb2346)
Location: include/net/sock.h:1579
Inline: True
Inline callers:
  - net/mptcp/pm.c:pm_worker
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
In kernel/bpf/cgroup.c (ffffffff81237201)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff814eece5)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff8189955c)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach_filter
  - drivers/net/tun.c:tun_attach_filter
```
```
In net/socket.c (ffffffff819dd3eb)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819e80f3)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
```
```
In net/core/stream.c (ffffffff819f5f95)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff81a35407)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (ffffffff81a3f755)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81a54b05)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff81a80b8b)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaa46d)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab166a)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
```
```
In net/ipv4/tcp.c (ffffffff81ab2049)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff81adb7ca)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81adbb6e)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ade40e)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff81aea865)
Location: include/net/sock.h:1592
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81aeeb61)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81b03efe)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17b68)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/xfrm/espintcp.c (ffffffff81b317e5)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b386ee)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81b41414)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5e3af)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
```
```
In net/ipv6/udp.c (ffffffff81b66a80)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b6a290)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff81b79e8d)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b7d60e)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
```
In net/packet/af_packet.c (ffffffff81b9b6aa)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff81b9c295)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
```
```
In net/mptcp/protocol.c (ffffffff81bbae60)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp6_release
  - net/mptcp/protocol.c:mptcp_release
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_getsockopt
  - net/mptcp/protocol.c:mptcp_setsockopt
  - net/mptcp/protocol.c:mptcp_setsockopt
  - net/mptcp/protocol.c:mptcp_setsockopt
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_check_fastclose
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:__mptcp_push_pending
```
```
In net/mptcp/subflow.c (ffffffff81bc35a3)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7359)
Location: include/net/sock.h:1592
Inline: True
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
In kernel/bpf/cgroup.c (ffffffff8123b71d)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff814f5a35)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff8188117a)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff819c363b)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819ce223)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
```
```
In net/core/stream.c (ffffffff819dc1dd)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff81a1c567)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (ffffffff81a4cdb8)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_wait_data
```
```
In net/core/sock_map.c (ffffffff81a51547)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff81a6a21b)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a95a1d)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bff7)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81a9d2d9)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff81ac683a)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ac69be)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ac9eae)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_pre_connect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff81ad5fa5)
Location: include/net/sock.h:1608
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81ada291)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81aefb7e)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b05736)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81b05d34)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b1f515)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b26367)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81b2f344)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4c62f)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
```
```
In net/ipv6/udp.c (ffffffff81b54c40)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b585c0)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/mcast.c (ffffffff81b61b37)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_close
```
```
In net/ipv6/ping.c (ffffffff81b689ba)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6c1ee)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
```
In net/packet/af_packet.c (ffffffff81b89b5e)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff81b8b355)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
```
```
In net/mptcp/protocol.c (ffffffff81bada99)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_wait_data
  - net/mptcp/protocol.c:__mptcp_push_pending
```
```
In net/mptcp/subflow.c (ffffffff81bb3c13)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbb02c)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
```
In net/mptcp/sockopt.c (ffffffff81bbca1a)
Location: include/net/sock.h:1608
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In kernel/bpf/cgroup.c (ffffffff812761a9)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff81550435)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff81912c09)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff81a72ecb)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81a7dad7)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
```
```
In net/core/stream.c (ffffffff81a8c41d)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff81acfd27)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/sock_map.c (ffffffff81b094c7)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff81b237f5)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b50e7d)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57897)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81b591a9)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff81b8504a)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81b851ce)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81b8873e)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_pre_connect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff81b94cc5)
Location: include/net/sock.h:1618
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81b994d5)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81bafb8e)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc8286)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/xfrm/espintcp.c (ffffffff81be4525)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81bece73)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81bf5716)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c1393f)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
```
```
In net/ipv6/udp.c (ffffffff81c1b500)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81c1f950)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/mcast.c (ffffffff81c295d5)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_close
```
```
In net/ipv6/ping.c (ffffffff81c30684)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81c3408e)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
```
In net/packet/af_packet.c (ffffffff81c55c6e)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff81c575f5)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
```
```
In net/mptcp/protocol.c (ffffffff81c7a4d6)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_push_pending
```
```
In net/mptcp/subflow.c (ffffffff81c82366)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8ab03)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
```
In net/mptcp/sockopt.c (ffffffff81c8c887)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In kernel/bpf/cgroup.c (ffffffff812c5baf)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff815e98a5)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff81a65c12)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff81be574b)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81bf1177)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
```
```
In net/core/stream.c (ffffffff81c01cbc)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff81c4d4b9)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/sock_map.c (ffffffff81c8f5ca)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff81cac216)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdde03)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5882)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81ceeff0)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff81d158d5)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81d15ca5)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81d19794)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff81d268a6)
Location: include/net/sock.h:1707
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81d2b314)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81d4315e)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5db1d)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/xfrm/espintcp.c (ffffffff81d7bb05)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81d85563)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81d8e707)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81daeff6)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
```
```
In net/ipv6/udp.c (ffffffff81db7c2f)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81dbc585)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/mcast.c (ffffffff81dc6a13)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_close
```
```
In net/ipv6/ping.c (ffffffff81dcddc0)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81dd196d)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
```
In net/packet/af_packet.c (ffffffff81df7cfa)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff81df8be5)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
```
```
In net/mptcp/protocol.c (ffffffff81e1ebc5)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_push_pending
```
```
In net/mptcp/subflow.c (ffffffff81e2809b)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
```
In net/mptcp/pm_netlink.c (ffffffff81e319dd)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
```
In net/mptcp/sockopt.c (ffffffff81e34d89)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff81e360eb)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
```
In net/mctp/af_mctp.c (ffffffff81e36ca7)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_bind
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
In kernel/bpf/cgroup.c (ffffffff8132b11f)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff81699205)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff81bf123b)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff81d92e0b)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81d9d937)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
```
```
In net/core/stream.c (ffffffff81db107c)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/sock_map.c (ffffffff81e4a9e9)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff81e69df6)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9e4f5)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8a82)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81eb21d5)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff81edbad5)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81edc0d5)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ee0b04)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff81eee226)
Location: include/net/sock.h:1723
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81ef2f34)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81f0c13b)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f277cd)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/xfrm/espintcp.c (ffffffff81f48bc5)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81f53013)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81f5c9c7)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/udp.c (ffffffff81f8ac93)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81f8c445)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/mcast.c (ffffffff81f97653)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_close
```
```
In net/ipv6/ping.c (ffffffff81f9efd5)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81fa2f8d)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
```
In net/packet/af_packet.c (ffffffff81fcc32a)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff81fcd185)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
```
```
In net/mptcp/protocol.c (ffffffff81ff555d)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_push_pending
```
```
In net/mptcp/pm_netlink.c (ffffffff8200a022)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
```
In net/mptcp/sockopt.c (ffffffff8200d9f9)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff8200ee0b)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
```
In net/mctp/af_mctp.c (ffffffff8200fd97)
Location: include/net/sock.h:1723
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_bind
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
In kernel/bpf/cgroup.c (ffffffff8135b2cb)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff816d16c5)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff81c49647)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff81e0120b)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81e0c1ae)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
```
```
In net/core/stream.c (ffffffff81e21570)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/sock_map.c (ffffffff81ea60e9)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff81ec5dbf)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efccf5)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_sock_set_pktinfo
  - net/ipv4/ip_sockglue.c:ip_sock_set_mtu_discover
  - net/ipv4/ip_sockglue.c:ip_sock_set_recverr
  - net/ipv4/ip_sockglue.c:ip_sock_set_freebind
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f07302)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81f1097b)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_sock_set_keepcnt
  - net/ipv4/tcp.c:tcp_sock_set_keepintvl
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_user_timeout
  - net/ipv4/tcp.c:tcp_sock_set_syncnt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_eof
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2e8b5)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
```
```
In net/ipv4/datagram.c (ffffffff81f3aba5)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81f3b165)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81f3ebff)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_splice_eof
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff81f4dbe6)
Location: include/net/sock.h:1714
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81f529e4)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81f6bdcb)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8748d)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/xfrm/espintcp.c (ffffffff81fa8a35)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81fb29ee)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81fbc6b7)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/udp.c (ffffffff81fe9774)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_splice_eof
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81fecc15)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/mcast.c (ffffffff81ff800d)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_close
```
```
In net/ipv6/ping.c (ffffffff81fffb19)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff8200384d)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
```
In net/packet/af_packet.c (ffffffff8202d9ae)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff82048ab5)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
```
```
In net/mptcp/protocol.c (ffffffff820762c3)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_push_pending
```
```
In net/mptcp/pm_netlink.c (ffffffff82086d17)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
```
In net/mptcp/sockopt.c (ffffffff8208a3c9)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff8208b9fb)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
```
In net/mctp/af_mctp.c (ffffffff8208c9b7)
Location: include/net/sock.h:1714
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_bind
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
In kernel/bpf/cgroup.c (ffffffff81383e82)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff8170dcf5)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff81cfee0e)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/socket.c (ffffffff81ebd90b)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81ec8b50)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
```
```
In net/core/stream.c (ffffffff81edf307)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/sock_map.c (ffffffff81f68ba9)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff81f8901f)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb647)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81fd4b5b)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_nodelay
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_eof
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff3715)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
```
```
In net/ipv4/datagram.c (ffffffff82000c95)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff82001275)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_bind
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff82004f5f)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_pre_connect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_splice_eof
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff82013d16)
Location: include/net/sock.h:1689
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff82018cc4)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_getname
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_bind_sk
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff8203239b)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_pre_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204eb0d)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/xfrm/espintcp.c (ffffffff82075d25)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_tx_work
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8207b410)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
```
In net/ipv6/af_inet6.c (ffffffff8208019a)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind_sk
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff82089ad7)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/udp.c (ffffffff820b6503)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_splice_eof
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_pre_connect
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff820ba815)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/mcast.c (ffffffff820c5c5d)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_close
```
```
In net/ipv6/ping.c (ffffffff820ce915)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_pre_connect
```
```
In net/ipv6/datagram.c (ffffffff820d261d)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
```
In net/packet/af_packet.c (ffffffff820fd42e)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff8211ae35)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
```
```
In net/mptcp/protocol.c (ffffffff8214ab61)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_push_pending
```
```
In net/mptcp/pm_netlink.c (ffffffff8215c4c7)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
```
In net/mptcp/sockopt.c (ffffffff8215fde9)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_ip_set
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
  - net/mptcp/sockopt.c:mptcp_setsockopt_v6
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff821617fb)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit
```
```
In net/mctp/af_mctp.c (ffffffff82162e87)
Location: include/net/sock.h:1689
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_bind
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
In kernel/bpf/cgroup.c (ffff80001028e534)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffff80001056ccac)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffff8000109dff08)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
```
```
In net/socket.c (ffff800010ba0d9c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffff800010badf78)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffff800010bbd6b4)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffff800010c02fe4)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (ffff800010c0f8a8)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffff800010c200dc)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffff800010c4ccd4)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffff800010c6656c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6ddf8)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffff800010c756dc)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffff800010c960e4)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffff800010c962ec)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffff800010c9989c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffff800010ca60d0)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv4/af_inet.c (ffff800010ca9d78)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffff800010cc0730)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3e08)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (ffff800010cf682c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffff800010cfe7b0)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1cae0)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d238c0)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d28248)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffff800010d3a548)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffff800010d3d2bc)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffff800010d5c5bc)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffff800010d5ede8)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
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
In kernel/bpf/cgroup.c (c04bd4a0)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (c0720504)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (c0ac2438)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (c0cc30c4)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (c0ccba14)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (c0cd96ec)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (c0d1c620)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (c0d261dc)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (c0d37af0)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (c0d5de48)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (c0d75d60)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c0d7ca1c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c0d83e10)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (c0da48c8)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da4b7c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c0da9960)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (c0db2878)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (c0db654c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (c0dcca28)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (c0dddcf4)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (c0dfd10c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (c0e06f44)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (c0e219f0)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv6/udp.c (c0e287c0)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2cc1c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (c0e3ca1c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (c0e40564)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (c0e5d7a4)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (c0e5e9c4)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
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
In kernel/bpf/cgroup.c (c000000000339ef0)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (c0000000006d1264)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (c000000000aa5168)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (c000000000c74d3c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (c000000000c8396c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (c000000000c96848)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (c000000000cec808)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (c000000000cfa694)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (c000000000d11f38)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (c000000000d4b9f8)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (c000000000d6aa90)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (c000000000d7458c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c000000000d7ce7c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (c000000000da7364)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (c000000000da7a24)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c000000000daad44)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (c000000000dba460)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv4/af_inet.c (c000000000dbf38c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (c000000000ddba6c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (c000000000df3190)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (c000000000e1cdcc)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (c000000000e2786c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4b0d8)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv6/udp.c (c000000000e54180)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c000000000e594f0)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (c000000000e6d740)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (c000000000e71534)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (c000000000e982b4)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (c000000000e9977c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
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
In kernel/bpf/cgroup.c (ffffffe0001c1644)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffe0003c1666)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffe0006261b6)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffe000738b04)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffe00073ff70)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffe00074baba)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffe0007823a4)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (ffffffe00078b3dc)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffe0007990d8)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffe0007b8bb8)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cd75e)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d3518)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffe0007d895e)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffe0007f5078)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffe0007f5482)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffe0007f710c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffe0008018e0)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffe00080481a)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffe000816ec0)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824c4c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffe000841eee)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffe0008493a4)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe0008601c0)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv6/udp.c (ffffffe000865c2c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffe000869a20)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffe0008771ec)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffe000879aae)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffe000892f04)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffe00089458c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
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
In kernel/bpf/cgroup.c (ffffffff811fd5f9)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff814746c5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff81789823)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff818ab80b)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818b50e3)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff818c294e)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff818ffae5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (ffffffff819089e5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81919168)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff8193f76e)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff8195543f)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195c2c3)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819627e5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff81981d85)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81982255)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81984695)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff8198fd6d)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (ffffffff819937c1)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff819a75a9)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7c9e)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff819d53ed)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff819dcb94)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f6fc2)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819feb65)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a02635)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff81a1119c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a13f65)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffff81a2ea19)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff81a308c5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
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
In kernel/bpf/cgroup.c (ffffffff811f0349)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff814650e5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff81769173)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In drivers/net/vxlan.c (ffffffff81770be7)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_stop
  - drivers/net/vxlan.c:vxlan_stop
  - drivers/net/vxlan.c:vxlan_open
  - drivers/net/vxlan.c:vxlan_open
```
```
In net/socket.c (ffffffff8186575b)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8186f033)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff8187c88e)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff818b9915)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (ffffffff818c27f5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff818d2f18)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff818f926e)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff8190ef2f)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915db3)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff8191c2d5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff8193b845)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8193bd15)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8193e155)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff8194982d)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (ffffffff8194d281)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81961069)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974a8e)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff819921ad)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81999954)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b3d82)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bb925)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819bf3f5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff819cdf5c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff819d0d25)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffff819ebc09)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff819edab5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
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
In kernel/bpf/cgroup.c (ffffffff811fb3c9)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff81470765)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff817b9bc3)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff818fc80b)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819060e3)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff8191394e)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff81950b15)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (ffffffff81959a15)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff8196a2f8)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff819908fe)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a4486)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst
  - net/netfilter/nf_conntrack_proto.c:getorigdst
```
```
In net/ipv4/ip_sockglue.c (ffffffff819bfc0f)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6a93)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819ccfb5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff819ec555)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819eca25)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819eee65)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff819fa60d)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (ffffffff819fe061)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81a11e49)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2271e)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81a3fe6d)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81a47614)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a61a42)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a695e5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a6d0b5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff81a7bc1c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a7e9e5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffff81a9a5c9)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff81a9c475)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
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
In kernel/bpf/cgroup.c (ffffffff81209f4a)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
```
In security/selinux/netlabel.c (ffffffff81487fd5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In drivers/net/tun.c (ffffffff817d5466)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_detach_filter
  - drivers/net/tun.c:tun_attach
```
```
In net/socket.c (ffffffff8191d80b)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81927113)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/stream.c (ffffffff81934ad1)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/filter.c (ffffffff819724e5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/core/skmsg.c (ffffffff8197bc35)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff8198c71c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_free
```
```
In net/netlink/af_netlink.c (ffffffff819b322e)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c95df)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819d05e3)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819d6b45)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/datagram.c (ffffffff819f6435)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819f6915)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_abort
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819f8fd5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_abort
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/devinet.c (ffffffff81a0493d)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/devinet.c:ip_mc_config
```
```
In net/ipv4/af_inet.c (ffffffff81a083f1)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_shutdown
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_listen
  - net/ipv4/af_inet.c:inet_autobind
```
```
In net/ipv4/ping.c (ffffffff81a1c7c0)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2db07)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81a4b9a8)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/addrconf.c (ffffffff81a53514)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_mc_config
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6df02)
Location: include/net/sock.h:1530
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a75bc5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a796d5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_destroy
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/ping.c (ffffffff81a8846c)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81a8b2a5)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/packet/af_packet.c (ffffffff81aa7319)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
```
In net/strparser/strparser.c (ffffffff81aa8655)
Location: include/net/sock.h:1530
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_sock_lock
```
</details>
</li>
</ul>

## Differences
