# Function: <code>sock_error</code>

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
In net/socket.c (ffffffff816ff7fb)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
```
```
In net/core/sock.c (ffffffff81702636)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff8170c9f9)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/core/stream.c (ffffffff8170df38)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81766461)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/af_inet.c (ffffffff81793786)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff817bf9a4)
Location: include/net/sock.h:1991
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/socket.c (ffffffff8176628b)
Location: include/net/sock.h:1956
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
```
```
In net/core/sock.c (ffffffff81769866)
Location: include/net/sock.h:1956
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff81774283)
Location: include/net/sock.h:1956
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81775658)
Location: include/net/sock.h:1956
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff817d3d53)
Location: include/net/sock.h:1956
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81800f8f)
Location: include/net/sock.h:1956
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8182c8bc)
Location: include/net/sock.h:1956
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/socket.c (ffffffff8179330b)
Location: include/net/sock.h:2022
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
```
```
In net/core/sock.c (ffffffff81796786)
Location: include/net/sock.h:2022
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff817a1596)
Location: include/net/sock.h:2022
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff817a28c7)
Location: include/net/sock.h:2022
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81803a96)
Location: include/net/sock.h:2022
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81831ec2)
Location: include/net/sock.h:2022
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8185e373)
Location: include/net/sock.h:2022
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/socket.c (ffffffff817b175f)
Location: include/net/sock.h:2046
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
```
```
In net/core/sock.c (ffffffff817b4b56)
Location: include/net/sock.h:2046
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff817c06e0)
Location: include/net/sock.h:2046
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff817c0b16)
Location: include/net/sock.h:2046
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81824628)
Location: include/net/sock.h:2046
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81845c40)
Location: include/net/sock.h:2046
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff818534a4)
Location: include/net/sock.h:2046
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81883744)
Location: include/net/sock.h:2046
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
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
In net/socket.c (ffffffff818298ff)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
```
```
In net/core/sock.c (ffffffff8182cd95)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff8183a110)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff8183a536)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff818a5f01)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff818c567b)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff818d32f9)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81903e49)
Location: include/net/sock.h:2060
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
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
In net/socket.c (ffffffff81873b5e)
Location: include/net/sock.h:2063
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
```
```
In net/core/sock.c (ffffffff81876b9f)
Location: include/net/sock.h:2063
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff81884880)
Location: include/net/sock.h:2063
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81884c76)
Location: include/net/sock.h:2063
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff818f78c3)
Location: include/net/sock.h:2063
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff8191cff7)
Location: include/net/sock.h:2063
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff819296dd)
Location: include/net/sock.h:2063
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8195bf81)
Location: include/net/sock.h:2063
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
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
In net/socket.c (ffffffff81892b2a)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff8189736f)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff818a4ae0)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff818a5396)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81925f1c)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff8194b5a7)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff8195888d)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81990793)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
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
In net/socket.c (ffffffff818dce0a)
Location: include/net/sock.h:2159
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff818e17bd)
Location: include/net/sock.h:2159
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff818f024b)
Location: include/net/sock.h:2159
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff818f06da)
Location: include/net/sock.h:2159
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81989aa7)
Location: include/net/sock.h:2159
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff819afc7e)
Location: include/net/sock.h:2159
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff819bd3da)
Location: include/net/sock.h:2159
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff819fbe7e)
Location: include/net/sock.h:2159
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
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
In net/socket.c (ffffffff8190db0a)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff819139ad)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff8192222b)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff8192262a)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff819c0f0b)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff819e690e)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff819f3fea)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81a32b0e)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
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
In net/socket.c (ffffffff819e208a)
Location: include/net/sock.h:2218
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff819e60e3)
Location: include/net/sock.h:2218
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff819f5c7f)
Location: include/net/sock.h:2218
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819f5ecc)
Location: include/net/sock.h:2218
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81aaba40)
Location: include/net/sock.h:2218
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81ad40db)
Location: include/net/sock.h:2218
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81ae3571)
Location: include/net/sock.h:2218
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81b276f6)
Location: include/net/sock.h:2218
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bac5de)
Location: include/net/sock.h:2218
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
In net/socket.c (ffffffff819e1d2a)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff819e54cb)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff819f573f)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819f59cc)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81ab694e)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81ae061b)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81af0970)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81b35fdf)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bbe1e1)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff81bc338d)
Location: include/net/sock.h:2239
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_error_report
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
In net/socket.c (ffffffff819c7d8a)
Location: include/net/sock.h:2270
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff819cb490)
Location: include/net/sock.h:2270
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff819db8d9)
Location: include/net/sock.h:2270
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819dbe5d)
Location: include/net/sock.h:2270
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81aa1b06)
Location: include/net/sock.h:2270
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81acc607)
Location: include/net/sock.h:2270
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81adc07c)
Location: include/net/sock.h:2270
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81b23bc9)
Location: include/net/sock.h:2270
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bae455)
Location: include/net/sock.h:2270
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff81bb36bd)
Location: include/net/sock.h:2270
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_error_report
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
In net/socket.c (ffffffff81a770da)
Location: include/net/sock.h:2319
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff81a7ab20)
Location: include/net/sock.h:2319
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff81a8bb29)
Location: include/net/sock.h:2319
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81a8c06d)
Location: include/net/sock.h:2319
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81b5da91)
Location: include/net/sock.h:2319
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81b8ae97)
Location: include/net/sock.h:2319
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81b9b2aa)
Location: include/net/sock.h:2319
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc8169)
Location: include/net/sock.h:2319
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81be800b)
Location: include/net/sock.h:2319
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81c7b786)
Location: include/net/sock.h:2319
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff81c81df9)
Location: include/net/sock.h:2319
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_error_report
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
In net/socket.c (ffffffff81bea3e8)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff81beea44)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff81c01365)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81c0190d)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81cec3e0)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81d1ac85)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81d2d105)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5d79f)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81d7f923)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81e2095e)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff81e2799d)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_error_report
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
In io_uring/net.c (ffffffff8179857c)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - io_uring/net.c:io_connect
```
```
In net/socket.c (ffffffff81d96c98)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff81d9b094)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/datagram.c (ffffffff81db06b5)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81db0cbd)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81eb498d)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81ee2225)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81ef4b8b)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27e9f)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81f4d613)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81ff7dd8)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff81fff873)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_error_report
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
In io_uring/net.c (ffffffff817d931b)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - io_uring/net.c:io_connect
```
```
In net/socket.c (ffffffff81e05308)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff81e0a284)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/datagram.c (ffffffff81e20b75)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81e21195)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81f12ed2)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81f41d25)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81f54557)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87ada)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81fad09e)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff820742bc)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
```
In net/mptcp/subflow.c (ffffffff8207b943)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_error_report
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
In io_uring/net.c (ffffffff8181d5a1)
Location: include/net/sock.h:2470
Inline: True
Inline callers:
  - io_uring/net.c:io_connect
```
```
In net/socket.c (ffffffff81ec1bc8)
Location: include/net/sock.h:2470
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff81ec6c74)
Location: include/net/sock.h:2470
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/datagram.c (ffffffff81edea45)
Location: include/net/sock.h:2470
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81edef05)
Location: include/net/sock.h:2470
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81fd7277)
Location: include/net/sock.h:2470
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff82007bb5)
Location: include/net/sock.h:2470
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff8201a7ad)
Location: include/net/sock.h:2470
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204f1fb)
Location: include/net/sock.h:2470
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff8207b511)
Location: include/net/sock.h:2470
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff8214a537)
Location: include/net/sock.h:2470
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_error_report
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
In net/socket.c (ffff800010ba4ba8)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffff800010bab3ec)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffff800010bbcce4)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffff800010bbd348)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffff800010c71288)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffff800010c99d54)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffff800010cab4bc)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffff800010cf22c0)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
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
In net/socket.c (c0cc5ad0)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (c0cc9fe8)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (c0cd8ea0)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (c0cd92a0)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (c0d803a4)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (c0daa344)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (c0db7ef4)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (c0dfa1c8)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
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
In net/socket.c (c000000000c78448)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (c000000000c81ca4)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (c000000000c95dd4)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (c000000000c96190)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (c000000000d785a0)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (c000000000dab3c4)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (c000000000dbfd38)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (c000000000e186fc)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
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
In net/socket.c (ffffffe00073a962)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffe00073ed2e)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffe00074b4e6)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffe00074b82a)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffe0007d6a36)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffe0007f8f20)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffe000804e1a)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffe00083f3d8)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
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
In net/socket.c (ffffffff818adb0a)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff818b39ad)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff818c222b)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff818c262a)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff81960d7b)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff8198677e)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81993d8a)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff819d219e)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
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
In net/socket.c (ffffffff81867a5a)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff8186d8fd)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff8187c16b)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff8187c56a)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff8191a86b)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff8194023e)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff8194d84a)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8198ef5e)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
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
In net/socket.c (ffffffff818feb0a)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff819049ad)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff8191322b)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff8191362a)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff819cb54b)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff819f0f4e)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff819fe62a)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81a3cc1e)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
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
In net/socket.c (ffffffff8191fb87)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffffffff81925a4d)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffffffff819343ab)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819347aa)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/ipv4/tcp.c (ffffffff819d50db)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff819f934d)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81a089ba)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81a481d6)
Location: include/net/sock.h:2169
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
</details>
</li>
</ul>

## Differences
