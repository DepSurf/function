# Function: <code>sock_intr_errno</code>

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
In net/core/sock.c (ffffffff81702794)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff8170cf6d)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/core/stream.c (ffffffff8170df76)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/netlink/af_netlink.c (ffffffff8174e448)
Location: include/net/sock.h:2104
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8176501b)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81766388)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/af_inet.c (ffffffff8179372e)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff817bf75a)
Location: include/net/sock.h:2104
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In net/core/sock.c (ffffffff817699dc)
Location: include/net/sock.h:2077
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81774238)
Location: include/net/sock.h:2077
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81775cb8)
Location: include/net/sock.h:2077
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff817ba5ef)
Location: include/net/sock.h:2077
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d159b)
Location: include/net/sock.h:2077
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff817d3900)
Location: include/net/sock.h:2077
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81800f33)
Location: include/net/sock.h:2077
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8182c7ba)
Location: include/net/sock.h:2077
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff817968f2)
Location: include/net/sock.h:2143
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff817a1543)
Location: include/net/sock.h:2143
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff817a2e77)
Location: include/net/sock.h:2143
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff817e9f8c)
Location: include/net/sock.h:2143
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81801400)
Location: include/net/sock.h:2143
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff8180364d)
Location: include/net/sock.h:2143
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81831e6d)
Location: include/net/sock.h:2143
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8185e271)
Location: include/net/sock.h:2143
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff817b4cc0)
Location: include/net/sock.h:2167
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff817bf63f)
Location: include/net/sock.h:2167
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff817c0ffc)
Location: include/net/sock.h:2167
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81809c52)
Location: include/net/sock.h:2167
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818218d2)
Location: include/net/sock.h:2167
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818241f3)
Location: include/net/sock.h:2167
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff818533dc)
Location: include/net/sock.h:2167
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81883b42)
Location: include/net/sock.h:2167
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff8182cf05)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81838fcf)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff8183aa1a)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81888bae)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a0656)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818a5bb1)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff818d322b)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81904253)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff81876d3f)
Location: include/net/sock.h:2188
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff818836b6)
Location: include/net/sock.h:2188
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff818851d5)
Location: include/net/sock.h:2188
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff818dc5ed)
Location: include/net/sock.h:2188
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f548b)
Location: include/net/sock.h:2188
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818f7119)
Location: include/net/sock.h:2188
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8192960d)
Location: include/net/sock.h:2188
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8195c1b7)
Location: include/net/sock.h:2188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff8189750f)
Location: include/net/sock.h:2274
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff818a4106)
Location: include/net/sock.h:2274
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff818a57e1)
Location: include/net/sock.h:2274
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81908fcd)
Location: include/net/sock.h:2274
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922dcb)
Location: include/net/sock.h:2274
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81925780)
Location: include/net/sock.h:2274
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff819587bd)
Location: include/net/sock.h:2274
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff819909c6)
Location: include/net/sock.h:2274
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff818e190a)
Location: include/net/sock.h:2280
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff818ef45e)
Location: include/net/sock.h:2280
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff818f0ad4)
Location: include/net/sock.h:2280
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff8196a332)
Location: include/net/sock.h:2280
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985783)
Location: include/net/sock.h:2280
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819896e8)
Location: include/net/sock.h:2280
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff819bd300)
Location: include/net/sock.h:2280
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff819fc02f)
Location: include/net/sock.h:2280
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff81913afe)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81921411)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81922a2e)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff819a0da2)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bc476)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819c0b5d)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff819f3f10)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81a32cbf)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff819e6110)
Location: include/net/sock.h:2353
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff819f50a8)
Location: include/net/sock.h:2353
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819f65d0)
Location: include/net/sock.h:2353
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81a7a57e)
Location: include/net/sock.h:2353
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa58d3)
Location: include/net/sock.h:2353
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
```
```
In net/ipv4/tcp.c (ffffffff81aab5d8)
Location: include/net/sock.h:2353
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81ae34a4)
Location: include/net/sock.h:2353
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81b279d9)
Location: include/net/sock.h:2353
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/mptcp/protocol.c (ffffffff81bac45a)
Location: include/net/sock.h:2353
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In net/core/sock.c (ffffffff819e5550)
Location: include/net/sock.h:2374
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff819f4ab1)
Location: include/net/sock.h:2374
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819f619c)
Location: include/net/sock.h:2374
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81a833e9)
Location: include/net/sock.h:2374
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafed9)
Location: include/net/sock.h:2374
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
```
```
In net/ipv4/tcp.c (ffffffff81ab645d)
Location: include/net/sock.h:2374
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81af0894)
Location: include/net/sock.h:2374
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81b3630d)
Location: include/net/sock.h:2374
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/mptcp/protocol.c (ffffffff81bbdf51)
Location: include/net/sock.h:2374
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In net/core/sock.c (ffffffff819cb64d)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff819dac41)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819dc333)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81a6c4b9)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c01e)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81aa161d)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81adbfd3)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81b23eea)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/mptcp/protocol.c (ffffffff81bae2c8)
Location: include/net/sock.h:2410
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
In net/core/sock.c (ffffffff81a7acdd)
Location: include/net/sock.h:2469
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81a8b2c1)
Location: include/net/sock.h:2469
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81a8c573)
Location: include/net/sock.h:2469
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81b25b17)
Location: include/net/sock.h:2469
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b578be)
Location: include/net/sock.h:2469
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81b5d5af)
Location: include/net/sock.h:2469
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81b9b203)
Location: include/net/sock.h:2469
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc8183)
Location: include/net/sock.h:2469
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81be8536)
Location: include/net/sock.h:2469
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/mptcp/protocol.c (ffffffff81c7b5d1)
Location: include/net/sock.h:2469
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
In net/core/sock.c (ffffffff81beec1b)
Location: include/net/sock.h:2592
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81c00a85)
Location: include/net/sock.h:2592
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81c01e12)
Location: include/net/sock.h:2592
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81cae6c2)
Location: include/net/sock.h:2592
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce58a9)
Location: include/net/sock.h:2592
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81cebee5)
Location: include/net/sock.h:2592
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81d2d05e)
Location: include/net/sock.h:2592
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5d7bf)
Location: include/net/sock.h:2592
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81d7f9dd)
Location: include/net/sock.h:2592
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/mptcp/protocol.c (ffffffff81e206ec)
Location: include/net/sock.h:2592
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In net/core/sock.c (ffffffff81d9b26b)
Location: include/net/sock.h:2638
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81dafd55)
Location: include/net/sock.h:2638
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81db11bf)
Location: include/net/sock.h:2638
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81e6bd00)
Location: include/net/sock.h:2638
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8aa9)
Location: include/net/sock.h:2638
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81eafec3)
Location: include/net/sock.h:2638
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81ef4aea)
Location: include/net/sock.h:2638
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27ebf)
Location: include/net/sock.h:2638
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81f4d6cd)
Location: include/net/sock.h:2638
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/mptcp/protocol.c (ffffffff81ff7b80)
Location: include/net/sock.h:2638
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In net/core/sock.c (ffffffff81e0a452)
Location: include/net/sock.h:2626
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81e1ffc5)
Location: include/net/sock.h:2626
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81e216c8)
Location: include/net/sock.h:2626
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81ec7d60)
Location: include/net/sock.h:2626
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f07329)
Location: include/net/sock.h:2626
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81f0e313)
Location: include/net/sock.h:2626
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81f544b7)
Location: include/net/sock.h:2626
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87b3f)
Location: include/net/sock.h:2626
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81fad168)
Location: include/net/sock.h:2626
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/mptcp/protocol.c (ffffffff82074049)
Location: include/net/sock.h:2626
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In net/core/sock.c (ffffffff81ec6e46)
Location: include/net/sock.h:2616
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81eddea5)
Location: include/net/sock.h:2616
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81edf4be)
Location: include/net/sock.h:2616
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81f8b172)
Location: include/net/sock.h:2616
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb66e)
Location: include/net/sock.h:2616
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81fd24b4)
Location: include/net/sock.h:2616
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8201a6f5)
Location: include/net/sock.h:2616
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204f21f)
Location: include/net/sock.h:2616
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff8207b5bd)
Location: include/net/sock.h:2616
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/mptcp/protocol.c (ffffffff82148599)
Location: include/net/sock.h:2616
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In net/core/sock.c (ffff800010bab5b8)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffff800010bbc7f4)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffff800010bbd7f4)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffff800010c4f49c)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6de1c)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffff800010c70f5c)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffff800010cab414)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffff800010cf26b8)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (c0cca168)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (c0cd8bdc)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (c0cd9804)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (c0d5f608)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (c0d7ca40)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c0d801b4)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (c0db7eac)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (c0dfa5f8)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (c000000000c81eb0)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (c000000000c95930)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (c000000000c96960)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (c000000000d4dcc0)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (c000000000d745b4)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c000000000d78188)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (c000000000dbfc1c)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (c000000000e18b80)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffe00073ee58)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffe00074a92e)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffe00074bb92)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffe0007bb0a0)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d34d8)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffe0007d674c)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffe000804db6)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffe00083f7dc)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff818b3afe)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff818c1411)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff818c2a2e)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81940c12)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195c2e6)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819609cd)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81993cb0)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff819d234f)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff8186da4e)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff8187b351)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff8187c96e)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff818fa702)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915dd6)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff8191a4bd)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8194d770)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8198f10f)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff81904afe)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81912411)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81913a2e)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81991da2)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6ab6)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819cb19d)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff819fe550)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81a3cdcf)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In net/core/sock.c (ffffffff81925b9e)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff819335b1)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81934bb1)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff819b4892)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819d0606)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819d4d2d)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81a088e0)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81a48382)
Location: include/net/sock.h:2301
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
</details>
</li>
</ul>

## Differences
