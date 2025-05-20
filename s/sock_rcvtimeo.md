# Function: <code>sock_rcvtimeo</code>

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
In net/core/datagram.c (ffffffff8170ca1e)
Location: include/net/sock.h:2086
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764f82)
Location: include/net/sock.h:2086
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff817662af)
Location: include/net/sock.h:2086
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff817bf348)
Location: include/net/sock.h:2086
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
In net/core/datagram.c (ffffffff81774535)
Location: include/net/sock.h:2059
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d1502)
Location: include/net/sock.h:2059
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff817d33e3)
Location: include/net/sock.h:2059
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/unix/af_unix.c (ffffffff8182c395)
Location: include/net/sock.h:2059
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff817a1836)
Location: include/net/sock.h:2125
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818013c2)
Location: include/net/sock.h:2125
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff8180313a)
Location: include/net/sock.h:2125
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/unix/af_unix.c (ffffffff8185de4c)
Location: include/net/sock.h:2125
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff817c0866)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81821894)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81823c4d)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81845c00)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/unix/af_unix.c (ffffffff8188336d)
Location: include/net/sock.h:2149
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff8183a286)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a0618)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818a5696)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff818c5640)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/unix/af_unix.c (ffffffff81903a6d)
Location: include/net/sock.h:2163
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In kernel/bpf/sockmap.c (ffffffff811cebc4)
Location: include/net/sock.h:2170
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
```
```
In net/core/datagram.c (ffffffff818849ca)
Location: include/net/sock.h:2170
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f53e8)
Location: include/net/sock.h:2170
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818f6e3f)
Location: include/net/sock.h:2170
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff8191cfbc)
Location: include/net/sock.h:2170
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/unix/af_unix.c (ffffffff8195bb99)
Location: include/net/sock.h:2170
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff818a4c3a)
Location: include/net/sock.h:2256
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922d28)
Location: include/net/sock.h:2256
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819254af)
Location: include/net/sock.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff8194b56c)
Location: include/net/sock.h:2256
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff81977e47)
Location: include/net/sock.h:2256
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819903b9)
Location: include/net/sock.h:2256
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff818f0395)
Location: include/net/sock.h:2262
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819856df)
Location: include/net/sock.h:2262
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81989180)
Location: include/net/sock.h:2262
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff819afc4d)
Location: include/net/sock.h:2262
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e19c9)
Location: include/net/sock.h:2262
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819fba95)
Location: include/net/sock.h:2262
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff81922375)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bc3d2)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819c05d5)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff819e68dd)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a188c9)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a32725)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff819f5dc5)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6fb1)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81aab0fd)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81ad40ad)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b099ef)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81b272b3)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81bac2a9)
Location: include/net/sock.h:2333
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
In net/core/datagram.c (ffffffff819f58c5)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab1641)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81ab6051)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81ae05ed)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17e09)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81b35bb8)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81bbdd60)
Location: include/net/sock.h:2354
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
In net/core/datagram.c (ffffffff819dba65)
Location: include/net/sock.h:2390
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bfa9)
Location: include/net/sock.h:2390
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81aa122e)
Location: include/net/sock.h:2390
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81acc5ce)
Location: include/net/sock.h:2390
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b05a0e)
Location: include/net/sock.h:2390
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/udp_bpf.c (ffffffff81b05d89)
Location: include/net/sock.h:2390
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81b23797)
Location: include/net/sock.h:2390
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81bade9c)
Location: include/net/sock.h:2390
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
In net/core/datagram.c (ffffffff81a8bcb5)
Location: include/net/sock.h:2449
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57849)
Location: include/net/sock.h:2449
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81b5d1bb)
Location: include/net/sock.h:2449
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81b8ae5e)
Location: include/net/sock.h:2449
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc8571)
Location: include/net/sock.h:2449
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc8a56)
Location: include/net/sock.h:2449
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81be7c54)
Location: include/net/sock.h:2449
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/unix/unix_bpf.c (ffffffff81beb7fd)
Location: include/net/sock.h:2449
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81c7b0c9)
Location: include/net/sock.h:2449
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
In net/core/datagram.c (ffffffff81c01510)
Location: include/net/sock.h:2572
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5830)
Location: include/net/sock.h:2572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81cebbe0)
Location: include/net/sock.h:2572
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81d1ac52)
Location: include/net/sock.h:2572
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5d8f7)
Location: include/net/sock.h:2572
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5e045)
Location: include/net/sock.h:2572
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81d7f502)
Location: include/net/sock.h:2572
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/unix/unix_bpf.c (ffffffff81d83a14)
Location: include/net/sock.h:2572
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81e20117)
Location: include/net/sock.h:2572
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
In net/core/datagram.c (ffffffff81db0870)
Location: include/net/sock.h:2618
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8a30)
Location: include/net/sock.h:2618
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81eafaa0)
Location: include/net/sock.h:2618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81ee21f2)
Location: include/net/sock.h:2618
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27b37)
Location: include/net/sock.h:2618
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff81f28815)
Location: include/net/sock.h:2618
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81f4d1f2)
Location: include/net/sock.h:2618
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/unix/unix_bpf.c (ffffffff81f51214)
Location: include/net/sock.h:2618
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81ff75f7)
Location: include/net/sock.h:2618
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
In net/core/datagram.c (ffffffff81e20d30)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f072b0)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81f0def0)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81f41cf2)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8793a)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff81f88374)
Location: include/net/sock.h:2606
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81facbd2)
Location: include/net/sock.h:2606
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/unix/unix_bpf.c (ffffffff81fb0b76)
Location: include/net/sock.h:2606
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82073adf)
Location: include/net/sock.h:2606
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
In net/core/datagram.c (ffffffff81edec00)
Location: include/net/sock.h:2596
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb5f5)
Location: include/net/sock.h:2596
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81fd1ff9)
Location: include/net/sock.h:2596
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff82007b82)
Location: include/net/sock.h:2596
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204efd7)
Location: include/net/sock.h:2596
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff8204fa94)
Location: include/net/sock.h:2596
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8207b032)
Location: include/net/sock.h:2596
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/unix/unix_bpf.c (ffffffff8207e216)
Location: include/net/sock.h:2596
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82148022)
Location: include/net/sock.h:2596
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
In net/core/datagram.c (ffff800010bbcebc)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6dda0)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffff800010c70ac8)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffff800010c99d28)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd43d4)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffff800010cf1eec)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (c0cd902c)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (c0d7c9b4)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c0d7fad0)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (c0daa2e4)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (c0dde590)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (c0df9e0c)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (c000000000c96014)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (c000000000d74500)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c000000000d77b20)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (c000000000dab380)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (c000000000df2418)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (c000000000e18254)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffe00074b5e2)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d34bc)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffe0007d631e)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffe0007f8ef0)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffe000825346)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffe00083f056)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff818c2375)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195c242)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81960445)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff8198674d)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7f59)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819d1db5)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff8187c2b5)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915d32)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81919f35)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff8194020d)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974d49)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8198eb75)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff81913375)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6a12)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819cac15)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff819f0f1d)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a229d9)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a3c835)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/datagram.c (ffffffff819344f5)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819d0562)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819d47a5)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff819f931f)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2ddcc)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a47de9)
Location: include/net/sock.h:2281
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
</details>
</li>
</ul>

## Differences
