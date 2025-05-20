# Function: <code>sk_tx_queue_clear</code>

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
In net/core/sock.c (ffffffff817007a8)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/core/sock.c:__sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff8174df28)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff8175705d)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81760a35)
Location: include/net/sock.h:1641
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764693)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff817682c7)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8176b2fc)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff8177a0ca)
Location: include/net/sock.h:1641
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff81783d58)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff817844cf)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81786c86)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81793339)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv4/ping.c (ffffffff817a2c73)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/unix/af_unix.c (ffffffff817bde59)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817dc162)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f0112)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/packet/af_packet.c (ffffffff81805a63)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff8176ab52)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/netlink/af_netlink.c (ffffffff817ba0db)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff817c332b)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff817ccd67)
Location: include/net/sock.h:1602
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0fef)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff817d4ba6)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff817d7abf)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff817e74f3)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffffffff817f130a)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff817f1a8f)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff817f3cc6)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8180115d)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_bind
```
```
In net/ipv4/ping.c (ffffffff818115b5)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/unix/af_unix.c (ffffffff8182adc9)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184ae42)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185ef5b)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/packet/af_packet.c (ffffffff81876627)
Location: include/net/sock.h:1602
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff81797c72)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/netlink/af_netlink.c (ffffffff817e9afd)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff817f1997)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fca87)
Location: include/net/sock.h:1658
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800eaf)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff818048b9)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81807a5f)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff81817a72)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffffffff818223aa)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8182286d)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81824aa6)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff818326bd)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_bind
```
```
In net/ipv4/ping.c (ffffffff81842ac5)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/unix/af_unix.c (ffffffff8185c849)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187cce2)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818910f7)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/packet/af_packet.c (ffffffff818aaba2)
Location: include/net/sock.h:1658
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff817b5832)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/netlink/af_netlink.c (ffffffff8180972e)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff8181327e)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181ce63)
Location: include/net/sock.h:1662
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820c0f)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff81824b43)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8182840f)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff81837e9c)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffffffff81843018)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818434a8)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff818457f6)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff818539de)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_bind
```
```
In net/ipv4/ping.c (ffffffff818643c6)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/unix/af_unix.c (ffffffff81880fd9)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a27e2)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (ffffffff818d1640)
Location: include/net/sock.h:1662
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff8182dcfb)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/netlink/af_netlink.c (ffffffff81888682)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff818928ca)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189bdd7)
Location: include/net/sock.h:1676
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fc05)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff818a6920)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff818a7923)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff818b75d4)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffffffff818c297e)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818c2e88)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff818c525c)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff818d3864)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_bind
```
```
In net/ipv4/ping.c (ffffffff818e4512)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa8d0)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/unix/af_unix.c (ffffffff81902169)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81925152)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (ffffffff81956599)
Location: include/net/sock.h:1676
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff818780c9)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/netlink/af_netlink.c (ffffffff818dc0a5)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff818e686a)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f03c7)
Location: include/net/sock.h:1687
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4c63)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff818fba19)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff818fca83)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff8190cf51)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffffffff819185ec)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81918991)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff8191ac2c)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81929d34)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff8193ab81)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff819513d6)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/unix/af_unix.c (ffffffff81959ace)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197d510)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (ffffffff819b19d5)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff819cbffc)
Location: include/net/sock.h:1687
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff818985a9)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffffffff818d69ee)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81908a72)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff819136c3)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191dfaa)
Location: include/net/sock.h:1738
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922163)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff81929970)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8192abfc)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff8193b268)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffffffff81946d65)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81947163)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff819493ec)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81959329)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff8196a871)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff819848b6)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/unix/af_unix.c (ffffffff8198ea33)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b33e0)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (ffffffff819e8db5)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a0522e)
Location: include/net/sock.h:1738
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff818e2b5d)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffffffff819242b0)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81969e9e)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff81975d01)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81980964)
Location: include/net/sock.h:1750
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985245)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff8198cab2)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8198de4d)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f635)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffffffff819ab3e5)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819ab7e3)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff819ada3c)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819bddfa)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff819d1526)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee5ac)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/unix/af_unix.c (ffffffff819fa19d)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a21ac0)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (ffffffff81a590f0)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a7486d)
Location: include/net/sock.h:1750
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff81914d3d)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffffffff819565c7)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff819a090e)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff819ac711)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b732f)
Location: include/net/sock.h:1760
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb335)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff819c342e)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819c4a1d)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff819d61df)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffffffff819e20b5)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819e24b3)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff819e4703)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819f4a0a)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81a08086)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2548c)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/unix/af_unix.c (ffffffff81a30e19)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a58530)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (ffffffff81a8f200)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81aab2b0)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff819e3715)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffffffff81a2a382)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff81a96bff)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9f84f)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5588)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff81aaeb29)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0b26)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac30e1)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/datagram.c (ffffffff81acf3bc)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81acfcb3)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81ad21b3)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81ae450b)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81af7e63)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1741b)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81b2335e)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b50a60)
Location: include/net/sock.h:1810
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff819e3265)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffffffff81a2add1)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff81aa0cdc)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa979f)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafb98)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff81ab8d90)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81abbb76)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff81aceb61)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/datagram.c (ffffffff81adb3c1)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81adbc33)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81ade2f0)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81af143b)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81b04dc6)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2644a)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81b31d4e)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5fd20)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
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
In net/core/sock.c (ffffffff819c92b5)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffffffff81a11f61)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff81a8bc1c)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9496f)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9aea8)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff81aa4043)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6b36)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab9d02)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/datagram.c (ffffffff81ac6422)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ac6a75)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81ac9910)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81adcbf4)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81af0626)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff81b13fe7)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81b1fa6e)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4e000)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/mptcp/sockopt.c (ffffffff81bbc087)
Location: include/net/sock.h:1838
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
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
In net/core/sock.c (ffffffff81a78655)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffffffff81acd289)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff81b46bac)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b4fdf0)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b56318)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff81b60258)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81b63136)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff81b77149)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/datagram.c (ffffffff81b84c32)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81b85299)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81b88184)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81b9bfe4)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81bb127f)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd80e7)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81be470e)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c1532b)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/mptcp/sockopt.c (ffffffff81c8bc27)
Location: include/net/sock.h:1878
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
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
In net/core/sock.c (ffffffff81bebf75)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffffffff81c4a94a)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/route.c (ffffffff81cd3c5d)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdfe09)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4433)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff81ceeb97)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1ddc)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06a7f)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/datagram.c (ffffffff81d154cf)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81d15d67)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81d19654)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81d2ded6)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81d44839)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6efab)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81d7bbfe)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db0b1b)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/mptcp/sockopt.c (ffffffff81e332a8)
Location: include/net/sock.h:1984
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/sock.c (ffffffff81d98945)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81e93e8d)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea01c9)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6d80)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff81eb1e10)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81eb664c)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecbce1)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/datagram.c (ffffffff81edbcbf)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81edc1a7)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81edffe4)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81ef5e06)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81f0d8d9)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3a901)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81f48cce)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f80c80)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/mptcp/sockopt.c (ffffffff8200c9a8)
Location: include/net/sock.h:2021
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/sock.c (ffffffff81e081a0)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81ef2629)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efea19)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05550)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff81f104be)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81f14a6c)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a8ab)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/datagram.c (ffffffff81f3ad8f)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81f3b23c)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81f3f4c0)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81f55666)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81f6d533)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a321)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81fa816e)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe0fe5)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/mptcp/sockopt.c (ffffffff820892fd)
Location: include/net/sock.h:2008
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/sock.c (ffffffff81ec4bf6)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/ipv4/route.c (ffffffff81fb6742)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc2c3f)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:__ip_sock_set_tos
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc98b6)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff81fd46b9)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8f5b)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff81fef46c)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/datagram.c (ffffffff82000e83)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8200134c)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff82007880)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8201bada)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff82033c83)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff82067681)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff8207545d)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820aeb69)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/mptcp/sockopt.c (ffffffff8215ec13)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In net/core/sock.c (ffff800010bada88)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffff800010bfdf94)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/netlink/af_netlink.c (ffff800010c4f088)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffff800010c5c8e4)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffff800010c68434)
Location: include/net/sock.h:1760
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c944)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffff800010c760ac)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (0)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffff800010c891ec)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffff800010c95d48)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffff800010c96bbc)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffff800010c99764)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffff800010caa920)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffff800010cc1294)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffff800010ce2948)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/unix/af_unix.c (ffff800010cf15dc)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1ded0)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (ffff800010d5c440)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffff800010d7f224)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (c0ccb610)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (c0d14e3c)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/netlink/af_netlink.c (c0d5f1e8)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (c0d6bf84)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (c0d774b0)
Location: include/net/sock.h:1760
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c0d7be4c)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (c0d847b8)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c0d859c0)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (c0d98244)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (c0da44d0)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da5404)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (c0da982c)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (c0db722c)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (c0dcd1e4)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (c0dec0d0)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/unix/af_unix.c (c0df7748)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (c0e224c8)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (c0e5c45c)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c0e79368)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (c000000000c833bc)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (c000000000cde6c4)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/netlink/af_netlink.c (c000000000d4d798)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (c000000000d5ecfc)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (c000000000d6cd90)
Location: include/net/sock.h:1760
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72c40)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (c000000000d7db34)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c000000000d7f878)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (c000000000d96464)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (c000000000da7570)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c000000000da7b18)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (c000000000daab94)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (c000000000dc0ac0)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (c000000000ddc848)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (c000000000e05a68)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/unix/af_unix.c (c000000000e14578)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4c12c)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (c000000000e97f20)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c000000000ebf45c)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffe00073fc88)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffffffe000779c58)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffe0007bad1c)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffe0007c5714)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007ce5e2)
Location: include/net/sock.h:1760
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2292)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffe0007d92aa)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffe0007da5e4)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea152)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffffffe0007f51c2)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffe0007f5522)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffe0007f7006)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffe00080567e)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffe000816416)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffe000831280)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/unix/af_unix.c (ffffffe00083d740)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe000860a38)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (ffffffe0008925d6)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffe0008ac316)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff818b4d3d)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffffffff818f6597)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff8194077e)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff8194c581)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff8195719f)
Location: include/net/sock.h:1760
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b1a5)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff8196329e)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8196488d)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff8197604f)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffffffff81981f25)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81982323)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff81984573)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819947aa)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff819a7e26)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff819c4b1c)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/unix/af_unix.c (ffffffff819d04a9)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f7bc0)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (ffffffff81a2e890)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a4a640)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff8186ec8d)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffffffff818b03c7)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff818fa26e)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff81906071)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff81910c8f)
Location: include/net/sock.h:1760
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914c95)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff8191cd8e)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8191e37d)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff8192fb0f)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffffffff8193b9e5)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8193bde3)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff8193e033)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8194e26a)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff819618e6)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff8198190c)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/unix/af_unix.c (ffffffff8198d269)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b4980)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (ffffffff819eba80)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a07230)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff81905d3d)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffffffff819475c7)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff8199190e)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff819b6d51)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c196f)
Location: include/net/sock.h:1760
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5975)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff819cda6e)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819cf05d)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff819e081f)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffffffff819ec6f5)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819ecaf3)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff819eed43)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819ff04a)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81a126c6)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f59c)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/unix/af_unix.c (ffffffff81a3af29)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a62640)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (ffffffff81a9a440)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ab64f0)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff81926d6d)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_prot_alloc
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_dst_check
```
```
In net/core/filter.c (ffffffff81968ed7)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff819b43fe)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff819c05e2)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cb35e)
Location: include/net/sock.h:1760
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf455)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffffffff819d75fe)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819d8bed)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea4df)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/datagram.c (ffffffff819f65df)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819f69e3)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffffffff819f8eb3)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81a0911a)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81a1d0c4)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3aefa)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/unix/af_unix.c (ffffffff81a45d89)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6eb40)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/packet/af_packet.c (ffffffff81aa7182)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ac2610)
Location: include/net/sock.h:1760
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
