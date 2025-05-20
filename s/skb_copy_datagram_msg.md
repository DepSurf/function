# Function: <code>skb_copy_datagram_msg</code>

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
In net/core/sock.c (ffffffff81701093)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff8170dcc3)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff8174c543)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761baa)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81767411)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8177076a)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/raw.c (ffffffff817845bc)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8178847f)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff817a33e2)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffff817bdac6)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff817e2df5)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff817e56a5)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff817f4e4e)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81804426)
Location: include/linux/skbuff.h:2803
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffff81767c13)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff817752e3)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff817b8257)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cdede)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff817d3b57)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff817e00f4)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/raw.c (ffffffff817f1b7c)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff817f5d36)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff818103f4)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8182aa3f)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff818512c3)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81853988)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81863efe)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81878499)
Location: include/linux/skbuff.h:3002
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffff81794c33)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff817a25d3)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff817e7d37)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdc3e)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff8180389f)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff818104c5)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/raw.c (ffffffff8182296c)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8182707e)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff818418f4)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8185c4bf)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81883119)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81885698)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff818965ae)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff818accef)
Location: include/linux/skbuff.h:3059
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffff817b2e23)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff817bfe0a)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff81807a46)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e076)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81823e11)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff81830410)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/raw.c (ffffffff818435b7)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff818471cc)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81863078)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81880aff)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff818a8216)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff818aba6e)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff818bcb38)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff818d532f)
Location: include/linux/skbuff.h:3131
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffff8182b113)
Location: include/linux/skbuff.h:3248
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff818399ba)
Location: include/linux/skbuff.h:3248
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff818865b6)
Location: include/linux/skbuff.h:3248
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189cf86)
Location: include/linux/skbuff.h:3248
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff818a5845)
Location: include/linux/skbuff.h:3248
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (ffffffff818c2f97)
Location: include/linux/skbuff.h:3248
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff818c6c2c)
Location: include/linux/skbuff.h:3248
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff818e31a8)
Location: include/linux/skbuff.h:3248
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81901c8f)
Location: include/linux/skbuff.h:3248
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff8192acc6)
Location: include/linux/skbuff.h:3248
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff8192e62e)
Location: include/linux/skbuff.h:3248
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff8193fc58)
Location: include/linux/skbuff.h:3248
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81959ddf)
Location: include/linux/skbuff.h:3248
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffff81875193)
Location: include/linux/skbuff.h:3259
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff818840f7)
Location: include/linux/skbuff.h:3259
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff818d9ed7)
Location: include/linux/skbuff.h:3259
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f1450)
Location: include/linux/skbuff.h:3259
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff818f6fb8)
Location: include/linux/skbuff.h:3259
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (ffffffff81918a60)
Location: include/linux/skbuff.h:3259
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8191d2dc)
Location: include/linux/skbuff.h:3259
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81939b15)
Location: include/linux/skbuff.h:3259
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81958885)
Location: include/linux/skbuff.h:3259
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81982d55)
Location: include/linux/skbuff.h:3259
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819875bc)
Location: include/linux/skbuff.h:3259
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81998a92)
Location: include/linux/skbuff.h:3259
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff819aef2a)
Location: include/linux/skbuff.h:3259
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffff81895a60)
Location: include/linux/skbuff.h:3336
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff818a516b)
Location: include/linux/skbuff.h:3336
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff819069d4)
Location: include/linux/skbuff.h:3336
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191efad)
Location: include/linux/skbuff.h:3336
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81925622)
Location: include/linux/skbuff.h:3336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (ffffffff8194722d)
Location: include/linux/skbuff.h:3336
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8194b88c)
Location: include/linux/skbuff.h:3336
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff819697a2)
Location: include/linux/skbuff.h:3336
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8198d485)
Location: include/linux/skbuff.h:3336
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819b966a)
Location: include/linux/skbuff.h:3336
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819bdbc9)
Location: include/linux/skbuff.h:3336
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff819cf3df)
Location: include/linux/skbuff.h:3336
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff819e58f7)
Location: include/linux/skbuff.h:3336
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffff818dff82)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff818efcf4)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff81967c74)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff819818ed)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff8198975e)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (ffffffff819ab8ad)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819aff7c)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff819d03dd)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819f8d05)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a27f17)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a2c6af)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a3e130)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a55327)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffff81912132)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff81921d14)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff8199e714)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b812d)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff819c0bd3)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (ffffffff819e257d)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819e6c19)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81a06f2d)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a2f955)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a5e980)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a631ef)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a74da0)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a8c3f7)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffff819e4c42)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff819f5a3a)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff81a78334)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2a4d)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81aab704)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (ffffffff81ad03bd)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ad4467)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81af752d)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b22bce)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81b237a5)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b57ee6)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b5c13f)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6eff0)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81b877c7)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81baa30a)
Location: include/linux/skbuff.h:3509
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_recvmsg_mskq
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
In net/core/sock.c (ffffffff819e4502)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff819f54fa)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff81a81132)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacd5d)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81ab6296)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/ipv4/raw.c (ffffffff81adc3cd)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ae09d2)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81b0440d)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b3134e)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81b3217f)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b66596)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b6a82f)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b7db20)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81b972a7)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81bba49a)
Location: include/linux/skbuff.h:3535
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_recvmsg_mskq
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
In net/core/sock.c (ffffffff819ca5a2)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff819db694)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff81a698ab)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a97fad)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81aa145e)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/ipv4/raw.c (ffffffff81ac733e)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81acca73)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81aef41d)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b1f07d)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81b1fe9f)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b5471b)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b58dcf)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6c710)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81b862a7)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81badfa9)
Location: include/linux/skbuff.h:3599
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In net/core/sock.c (ffffffff81a79b42)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff81a8af04)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff81b22e5b)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b5343d)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81b5d3f6)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/ipv4/raw.c (ffffffff81b85b5e)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81b8b3fc)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81bb099d)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81be3bbd)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81be4a2f)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81c1bbb8)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81c20387)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81c345fc)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81c52667)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81c7b219)
Location: include/linux/skbuff.h:3636
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In net/core/sock.c (ffffffff81bec8d0)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff81c0056b)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff81caba67)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdfb61)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81cebdf1)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/ipv4/raw.c (ffffffff81d15e9f)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81d1bda3)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81d43f43)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81d7b173)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81d7bfbc)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81db834a)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81dbd0ee)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81dd1f2e)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81df560d)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81e2026f)
Location: include/linux/skbuff.h:4009
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff81e36ec7)
Location: include/linux/skbuff.h:4009
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
In net/core/sock.c (ffffffff81d9b360)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff81daf99b)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff81e68887)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9ff11)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81eafca9)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/ipv4/raw.c (ffffffff81edcd2f)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ee2c93)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81f0d413)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81f47e93)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81f4910c)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81f8837a)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81f8d10e)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81fa338e)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81fc94bd)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81ff774a)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff820108e7)
Location: include/linux/skbuff.h:3905
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
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
In net/core/sock.c (ffffffff81e09730)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff81e1fc0b)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff81ec46f2)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe761)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81f0e0f9)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/ipv4/raw.c (ffffffff81f3bf7f)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81f4252b)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81f6d073)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81fa7998)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81fa8cbf)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81fe8c8a)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81fed8de)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff82003c3d)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff8202ba6c)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff82073c38)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff8208d097)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
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
In net/core/sock.c (ffffffff81ec6120)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff81edd2bb)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff81f87ab2)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc2981)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81fd257c)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/ipv4/raw.c (ffffffff8200209f)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff82008516)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff820337e3)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff82074c58)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff820761bf)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff820b67c8)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff820bb4ee)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff820d29ed)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff820fb51c)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff82148189)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff82163557)
Location: include/linux/skbuff.h:3967
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
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
In net/core/sock.c (ffff800010ba9b78)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffff800010bbc3b4)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffff800010c4d434)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffff800010c694d8)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffff800010c70fc0)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (ffff800010c963c8)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffff800010c9d130)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffff800010cbfeac)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffff800010ceec20)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffff800010d25e80)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d28520)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffff800010d3d7b8)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffff800010d57c0c)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (c0cc8284)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (c0cd880c)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (c0d5c588)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (c0d786bc)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (c0d800a4)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (c0da5688)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (c0daa6a4)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (c0dcc384)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (c0df6e8c)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (c0e2a2a4)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2d5a0)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (c0e409bc)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (c0e59b64)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (c000000000c7f298)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (c000000000c956a0)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (c000000000d49fcc)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e114)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (c000000000d78240)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (c000000000da7ca4)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (c000000000dac52c)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (c000000000ddb1ac)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (c000000000e13c40)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (c000000000e53dcc)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c000000000e598b0)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (c000000000e71ba8)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (c000000000e92c9c)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffe00073d110)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffe00074b0e0)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffe0007b91d0)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf3b8)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffe0007d650e)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (ffffffe0007f560a)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffe0007f93a6)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffe000816974)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffe00083bd1a)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffe00086536a)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffe000869d98)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffe000879ef4)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffe00088f8ca)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffff818b2132)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff818c1d14)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff8193e584)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff81957f9d)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81960a43)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (ffffffff819823ed)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81986a89)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff819a6ccd)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819cefe5)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819fe010)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a0287f)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a14430)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a2ba87)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffff8186c082)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff8187bc54)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff818f8084)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911a8d)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff8191a533)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (ffffffff8193bead)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81940549)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff8196078d)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8198bda5)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819badd0)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819bf63f)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff819d11f0)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff819e8c77)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffff81903132)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff81912d14)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff8198f714)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c276d)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff819cb213)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (ffffffff819ecbbd)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819f1259)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81a1156d)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a39a65)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a68a90)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a6d2ff)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a7eeb0)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a97637)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/core/sock.c (ffffffff81924112)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/datagram.c (ffffffff81933e94)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/netlink/af_netlink.c (ffffffff819b1ff4)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc16d)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff819d4da3)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/raw.c (ffffffff819f6aad)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819faf39)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81a1bedd)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a458b5)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_actor
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a7507b)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a7991f)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a8b770)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81aa3f57)
Location: include/linux/skbuff.h:3488
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
</details>
</li>
</ul>

## Differences
