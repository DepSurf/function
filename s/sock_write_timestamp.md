# Function: <code>sock_write_timestamp</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818913ac)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff81895b20)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
```
```
In net/compat.c (ffffffff818f3ea9)
Location: include/net/sock.h:2327
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191f13f)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff8194736d)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8194bc35)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff8196989b)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819b96a0)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819bdd84)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff819cf51e)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff819e5c78)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (ffffffff818db09c)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff818e0047)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981a93)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff819ab9ed)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819b03ca)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff819d04ee)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a283f3)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a2c86e)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a3e273)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a556da)
Location: include/net/sock.h:2333
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (ffffffff8190d1ec)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff819121f7)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b82d3)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff819e26bd)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819e7083)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81a0703e)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a5ee7c)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a633aa)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a74ee3)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a8c7a5)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (ffffffff819dfeca)
Location: include/net/sock.h:2406
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff819e4d07)
Location: include/net/sock.h:2406
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2bf3)
Location: include/net/sock.h:2406
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81ad04f7)
Location: include/net/sock.h:2406
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ad4856)
Location: include/net/sock.h:2406
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81af763e)
Location: include/net/sock.h:2406
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b5837d)
Location: include/net/sock.h:2406
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b5c293)
Location: include/net/sock.h:2406
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6f133)
Location: include/net/sock.h:2406
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81b87b18)
Location: include/net/sock.h:2406
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (ffffffff819df68a)
Location: include/net/sock.h:2427
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff819e45c7)
Location: include/net/sock.h:2427
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacf03)
Location: include/net/sock.h:2427
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81adc507)
Location: include/net/sock.h:2427
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ae0da3)
Location: include/net/sock.h:2427
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81b0451e)
Location: include/net/sock.h:2427
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b669dc)
Location: include/net/sock.h:2427
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b6a983)
Location: include/net/sock.h:2427
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b7dc63)
Location: include/net/sock.h:2427
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81b975f8)
Location: include/net/sock.h:2427
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (ffffffff819c6122)
Location: include/net/sock.h:2463
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff819ca667)
Location: include/net/sock.h:2463
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a98153)
Location: include/net/sock.h:2463
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81ac7474)
Location: include/net/sock.h:2463
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81acceb5)
Location: include/net/sock.h:2463
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81aef52e)
Location: include/net/sock.h:2463
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b54bdc)
Location: include/net/sock.h:2463
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b58f23)
Location: include/net/sock.h:2463
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6c853)
Location: include/net/sock.h:2463
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81b86601)
Location: include/net/sock.h:2463
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (ffffffff81a74d72)
Location: include/net/sock.h:2522
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff81a79c07)
Location: include/net/sock.h:2522
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b535e3)
Location: include/net/sock.h:2522
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81b85c94)
Location: include/net/sock.h:2522
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81b8b838)
Location: include/net/sock.h:2522
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81bb0aaf)
Location: include/net/sock.h:2522
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81c1c06a)
Location: include/net/sock.h:2522
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81c204d1)
Location: include/net/sock.h:2522
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81c3473c)
Location: include/net/sock.h:2522
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81c529c1)
Location: include/net/sock.h:2522
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (ffffffff81be7a96)
Location: include/net/sock.h:2645
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
```
```
In net/core/sock.c (ffffffff81bec9a7)
Location: include/net/sock.h:2645
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdfd1e)
Location: include/net/sock.h:2645
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81d15fef)
Location: include/net/sock.h:2645
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81d1c1df)
Location: include/net/sock.h:2645
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81d4403f)
Location: include/net/sock.h:2645
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81db8871)
Location: include/net/sock.h:2645
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81dbd2be)
Location: include/net/sock.h:2645
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81dd207f)
Location: include/net/sock.h:2645
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81df5a02)
Location: include/net/sock.h:2645
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff81e3706a)
Location: include/net/sock.h:2645
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
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
In net/socket.c (ffffffff81d93f5b)
Location: include/net/sock.h:2691
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
```
```
In net/core/sock.c (ffffffff81d9b436)
Location: include/net/sock.h:2691
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea00b5)
Location: include/net/sock.h:2691
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81edce79)
Location: include/net/sock.h:2691
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ee3087)
Location: include/net/sock.h:2691
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81f0d50e)
Location: include/net/sock.h:2691
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81f88869)
Location: include/net/sock.h:2691
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81f8d270)
Location: include/net/sock.h:2691
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81fa34de)
Location: include/net/sock.h:2691
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81fc984b)
Location: include/net/sock.h:2691
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff82010a8a)
Location: include/net/sock.h:2691
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
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
In net/socket.c (ffffffff81e01ac4)
Location: include/net/sock.h:2679
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
```
```
In net/core/sock.c (ffffffff81e09806)
Location: include/net/sock.h:2679
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe905)
Location: include/net/sock.h:2679
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81f3c0cb)
Location: include/net/sock.h:2679
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81f4292a)
Location: include/net/sock.h:2679
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81f6d16e)
Location: include/net/sock.h:2679
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81fe9192)
Location: include/net/sock.h:2679
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81feda4a)
Location: include/net/sock.h:2679
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff82003d91)
Location: include/net/sock.h:2679
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff8202be2c)
Location: include/net/sock.h:2679
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff8208d258)
Location: include/net/sock.h:2679
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
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
In net/socket.c (ffffffff81ebe486)
Location: include/net/sock.h:2669
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
```
```
In net/core/sock.c (ffffffff81ec61f9)
Location: include/net/sock.h:2669
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc2b2d)
Location: include/net/sock.h:2669
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff820021ef)
Location: include/net/sock.h:2669
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8200892f)
Location: include/net/sock.h:2669
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff820338e0)
Location: include/net/sock.h:2669
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff820b6c9a)
Location: include/net/sock.h:2669
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff820bb65b)
Location: include/net/sock.h:2669
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff820d2b44)
Location: include/net/sock.h:2669
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff820fb8dd)
Location: include/net/sock.h:2669
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff82163719)
Location: include/net/sock.h:2669
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
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
In net/socket.c (ffff800010ba2140)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffff800010ba9c6c)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffff800010c69658)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffff800010c96510)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffff800010c9d598)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffff800010cc0138)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffff800010d262fc)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d286b4)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffff800010d3d8e8)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffff800010d57f38)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (c0cc48f0)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (c0cc8350)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (c0d78860)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (c0da57d0)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (c0daab8c)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (c0dcc438)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (c0e2a718)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2d7b0)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (c0e40afc)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (c0e59ed4)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (c000000000c76e84)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (c000000000c7f3e4)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e314)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (c000000000da7e50)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (c000000000dac778)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (c000000000ddb530)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (c000000000e54078)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c000000000e59b18)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (c000000000e71d44)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (c000000000e930ac)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (ffffffe00073a1e2)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffe00073d1e6)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf4fc)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffe0007f5720)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffe0007f9586)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffe000816be8)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffe000865566)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffe000869f06)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffe00087a014)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffe00088fbca)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (ffffffff818ad1ec)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff818b21f7)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81958143)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff8198252d)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81986ef3)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff819a6dde)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819fe50c)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a02a3a)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a14573)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a2be35)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (ffffffff8186713c)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff8186c147)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911c33)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff8193bfed)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819409b3)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff8196089e)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819bb2cc)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819bf7fa)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff819d1333)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff819e9025)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (ffffffff818fe1ec)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff819031f7)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c2913)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff819eccfd)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819f16c3)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81a1167e)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a68f8c)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a6d4ba)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a7eff3)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81a979e5)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/socket.c (ffffffff8191f27c)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff819241d7)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc313)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff819f6bed)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819fb39e)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81a1bfee)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a75577)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a79ada)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a8b8b3)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (ffffffff81aa4305)
Location: include/net/sock.h:2354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
</details>
</li>
</ul>

## Differences
