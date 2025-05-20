# Function: <code>skb_hwtstamps</code>

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
In net/socket.c (ffffffff816fcc8f)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (0)
Location: include/linux/skbuff.h:1116
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:1116
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/skbuff.h:1116
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/skbuff.h:1116
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/skbuff.h:1116
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81802d8d)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff81764c78)
Location: include/linux/skbuff.h:1207
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81767ccb)
Location: include/linux/skbuff.h:1207
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff8176edb8)
Location: include/linux/skbuff.h:1207
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff817ce05c)
Location: include/linux/skbuff.h:1207
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff818104d8)
Location: include/linux/skbuff.h:1207
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81864037)
Location: include/linux/skbuff.h:1207
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff8187411d)
Location: include/linux/skbuff.h:1207
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff81791cf8)
Location: include/linux/skbuff.h:1222
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81794ceb)
Location: include/linux/skbuff.h:1222
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff8179c2e1)
Location: include/linux/skbuff.h:1222
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fddc3)
Location: include/linux/skbuff.h:1222
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff818419d8)
Location: include/linux/skbuff.h:1222
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff818966e7)
Location: include/linux/skbuff.h:1222
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff818a870d)
Location: include/linux/skbuff.h:1222
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff817af2d8)
Location: include/linux/skbuff.h:1215
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff817b2ed7)
Location: include/linux/skbuff.h:1215
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff817bce0f)
Location: include/linux/skbuff.h:1215
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e19d)
Location: include/linux/skbuff.h:1215
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff818630be)
Location: include/linux/skbuff.h:1215
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff818bcc45)
Location: include/linux/skbuff.h:1215
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff818cef4f)
Location: include/linux/skbuff.h:1215
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff81827418)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8182b1c7)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81833959)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189d0ad)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff818a5e06)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b83eb)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
```
```
In net/ipv4/ping.c (ffffffff818e31ee)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938922)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff8193fd65)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81953edf)
Location: include/linux/skbuff.h:1273
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff818707fa)
Location: include/linux/skbuff.h:1284
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff818751ce)
Location: include/linux/skbuff.h:1284
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff8187f4a1)
Location: include/linux/skbuff.h:1284
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f146a)
Location: include/linux/skbuff.h:1284
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff818f767f)
Location: include/linux/skbuff.h:1284
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190dd4b)
Location: include/linux/skbuff.h:1284
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
```
```
In net/ipv4/ping.c (ffffffff81939bd6)
Location: include/linux/skbuff.h:1284
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819917c2)
Location: include/linux/skbuff.h:1284
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81998ae4)
Location: include/linux/skbuff.h:1284
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff819ad775)
Location: include/linux/skbuff.h:1284
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff8189130a)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81895a9b)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff818a0271)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191efc7)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81925cee)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8192b5c2)
Location: include/linux/skbuff.h:1322
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193c138)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff81969863)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c7fff)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff819cf431)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff819e40e5)
Location: include/linux/skbuff.h:1322
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff818daffa)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff818dffbd)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff818eac83)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981906)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff819899aa)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8198e855)
Location: include/linux/skbuff.h:1410
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a0568)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff819d04b0)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a36a6f)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81a3e17e)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a52fd5)
Location: include/linux/skbuff.h:1410
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff8190d14a)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8191216d)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff8191cdf3)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b8146)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff819c0e20)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff819c5595)
Location: include/linux/skbuff.h:1407
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d7128)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff81a07000)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6d58f)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81a74dee)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a89bc5)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff819dfeaa)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff819e4c7d)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff819ef0f4)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2a66)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81aab77d)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff81ab081e)
Location: include/linux/skbuff.h:1413
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac3b6d)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff81af7600)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66a74)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81b6f03e)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81b869a5)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/packet/af_packet.c:__packet_set_timestamp
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
In net/socket.c (ffffffff819df66a)
Location: include/linux/skbuff.h:1434
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff819e453d)
Location: include/linux/skbuff.h:1434
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff819eed94)
Location: include/linux/skbuff.h:1434
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacd76)
Location: include/linux/skbuff.h:1434
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81ab669a)
Location: include/linux/skbuff.h:1434
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81abb7fe)
Location: include/linux/skbuff.h:1434
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81acf5fd)
Location: include/linux/skbuff.h:1434
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff81b044e0)
Location: include/linux/skbuff.h:1434
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b74fd4)
Location: include/linux/skbuff.h:1434
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81b7db6e)
Location: include/linux/skbuff.h:1434
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81b963e5)
Location: include/linux/skbuff.h:1434
Inline: True
Inline callers:
  - net/packet/af_packet.c:__packet_set_timestamp
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
In net/socket.c (ffffffff819c6095)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff819ca5e6)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff819d7454)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a97fcf)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81a9d50a)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
```
```
In net/ipv4/tcp_input.c (ffffffff81aa8208)
Location: include/linux/skbuff.h:1441
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81aba749)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff81aef4f9)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b63a4c)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81b6c767)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81b84593)
Location: include/linux/skbuff.h:1441
Inline: True
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
In net/socket.c (ffffffff81a74ce5)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81a79b86)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81a85c94)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b5345f)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81b5d10a)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
```
```
In net/ipv4/tcp_input.c (ffffffff81b63db8)
Location: include/linux/skbuff.h:1454
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b77a29)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff81bb0a79)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2b50c)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81c34656)
Location: include/linux/skbuff.h:1454
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81c50a23)
Location: include/linux/skbuff.h:1454
Inline: True
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
In net/socket.c (ffffffff81be79a5)
Location: include/linux/skbuff.h:1792
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81bec928)
Location: include/linux/skbuff.h:1792
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81bf9ebb)
Location: include/linux/skbuff.h:1792
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdfb83)
Location: include/linux/skbuff.h:1792
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81cebafa)
Location: include/linux/skbuff.h:1792
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
```
```
In net/ipv4/tcp_input.c (ffffffff81cf22cc)
Location: include/linux/skbuff.h:1792
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_try_coalesce
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d07959)
Location: include/linux/skbuff.h:1792
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff81d4400f)
Location: include/linux/skbuff.h:1792
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc8a5c)
Location: include/linux/skbuff.h:1792
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81dd1fa1)
Location: include/linux/skbuff.h:1792
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81df14f3)
Location: include/linux/skbuff.h:1792
Inline: True
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
In net/socket.c (ffffffff81d93e65)
Location: include/linux/skbuff.h:1637
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81d9b3b8)
Location: include/linux/skbuff.h:1637
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81da8d8a)
Location: include/linux/skbuff.h:1637
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9ff33)
Location: include/linux/skbuff.h:1637
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81eaf9aa)
Location: include/linux/skbuff.h:1637
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
```
```
In net/ipv4/tcp_input.c (ffffffff81eb694c)
Location: include/linux/skbuff.h:1637
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_try_coalesce
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecd6c9)
Location: include/linux/skbuff.h:1637
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff81f0d4df)
Location: include/linux/skbuff.h:1637
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f99e8c)
Location: include/linux/skbuff.h:1637
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81fa3401)
Location: include/linux/skbuff.h:1637
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81fc5473)
Location: include/linux/skbuff.h:1637
Inline: True
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
In net/socket.c (ffffffff81e01a05)
Location: include/linux/skbuff.h:1666
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81e09788)
Location: include/linux/skbuff.h:1666
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81e19e8a)
Location: include/linux/skbuff.h:1666
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe783)
Location: include/linux/skbuff.h:1666
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81f0ddfa)
Location: include/linux/skbuff.h:1666
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
```
```
In net/ipv4/tcp_input.c (ffffffff81f14d6d)
Location: include/linux/skbuff.h:1666
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_try_coalesce
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c389)
Location: include/linux/skbuff.h:1666
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff81f6d13f)
Location: include/linux/skbuff.h:1666
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa85c)
Location: include/linux/skbuff.h:1666
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff82003cad)
Location: include/linux/skbuff.h:1666
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff82026083)
Location: include/linux/skbuff.h:1666
Inline: True
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
In net/socket.c (ffffffff81ebe3c7)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81ec616f)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81ed7417)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc299b)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81fd1f0a)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
```
```
In net/ipv4/tcp_input.c (ffffffff81fd92a4)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_try_coalesce
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff1309)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff820338a7)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c854c)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff820d2a55)
Location: include/linux/skbuff.h:1673
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff820f5a93)
Location: include/linux/skbuff.h:1673
Inline: True
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
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e6fb8)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In net/socket.c (ffff800010ba20ac)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffff800010ba9be4)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffff800010bb74dc)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffff800010c694f4)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffff800010c711ec)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffff800010c79f4c)
Location: include/linux/skbuff.h:1407
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8a180)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffff800010cbff68)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d35e0c)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffff800010d3d838)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffff800010d56a04)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In drivers/net/ethernet/freescale/fec_main.c (c0acbd34)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad0e14)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_rx_timestamp
```
```
In net/socket.c (c0cc483c)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (c0cc82a8)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (c0cd41c0)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (c0d786cc)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (c0d802e4)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (c0d8679c)
Location: include/linux/skbuff.h:1407
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c0d99444)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (c0dcc3f0)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (c0e383d4)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (c0e409f8)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (c0e572dc)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (c000000000c76db4)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (c000000000c7f330)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (c000000000c8f044)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e134)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (c000000000d784a8)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (c000000000d80a90)
Location: include/linux/skbuff.h:1407
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9790c)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (c000000000ddb2c0)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (c000000000e68020)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (c000000000e71c50)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (c000000000e8ff28)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffe00073a16a)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffe00073d16c)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffe000746ff4)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf3d0)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffe0007d69e2)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffe0007db28c)
Location: include/linux/skbuff.h:1407
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eae7e)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffe0008169f8)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008733a2)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffe000879f50)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffe00088e3f8)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff818ad14a)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff818b216d)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff818bcdf3)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81957fb6)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff81960c90)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff81965405)
Location: include/linux/skbuff.h:1407
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81976f98)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff819a6da0)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0cc1f)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81a1447e)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a29255)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff8186709a)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8186c0bd)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff81876d33)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911aa6)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff8191a780)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8191eef5)
Location: include/linux/skbuff.h:1407
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81930a58)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff81960860)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c99df)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff819d123e)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff819e6445)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff818fe14a)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8190316d)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff8190ddf3)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c2786)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff819cb460)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff819cfbd5)
Location: include/linux/skbuff.h:1407
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e1768)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff81a11640)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7769f)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81a7eefe)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a94e05)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff8191f1da)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8192414d)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/core/skbuff.c (ffffffff8192ef23)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_complete_tx_timestamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc186)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/tcp.c (ffffffff819d4ff0)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff819d9765)
Location: include/linux/skbuff.h:1407
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb498)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_fill_cb
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/ping.c (ffffffff81a1bfb0)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a83d8f)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_fill_cb
```
```
In net/ipv6/datagram.c (ffffffff81a8b7be)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81aa10d5)
Location: include/linux/skbuff.h:1407
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
```
</details>
</li>
</ul>

## Differences
