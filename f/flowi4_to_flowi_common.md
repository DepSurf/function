# Function: <code>flowi4_to_flowi_common</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa9489)
Location: include/net/flow.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafce4)
Location: include/net/flow.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad102d)
Location: include/net/flow.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81adb39a)
Location: include/net/flow.h:198
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81adcd3c)
Location: include/net/flow.h:198
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ae1cd2)
Location: include/net/flow.h:198
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff81ae8826)
Location: include/net/flow.h:198
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81af0310)
Location: include/net/flow.h:198
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
```
```
In net/ipv4/igmp.c (0)
Location: include/net/flow.h:198
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81b03ea3)
Location: include/net/flow.h:198
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/flow.h:198
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81b15ac1)
Location: include/net/flow.h:198
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/ip_output.c (ffffffff81a94653)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9aff4)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abc021)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81ac63fb)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ac7dda)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81acb9a8)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (ffffffff81ad45b6)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81adb9c0)
Location: include/net/flow.h:195
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/flow.h:195
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81aefb23)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/flow.h:195
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81b038cf)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/ip_output.c (ffffffff81b4fad3)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b566c2)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/net/flow.h:195
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff81b84c0b)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81b8663a)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (0)
Location: include/net/flow.h:195
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b93fcb)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/flow.h:195
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/flow.h:195
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81bafb33)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/flow.h:195
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81bc5b5f)
Location: include/net/flow.h:195
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/ip_output.c (ffffffff81cdd552)
Location: include/net/flow.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce3fa5)
Location: include/net/flow.h:199
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/net/flow.h:199
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff81d154a4)
Location: include/net/flow.h:199
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81d17016)
Location: include/net/flow.h:199
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (0)
Location: include/net/flow.h:199
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81d25461)
Location: include/net/flow.h:199
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/flow.h:199
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/flow.h:199
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81d430fb)
Location: include/net/flow.h:199
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/flow.h:199
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81d5ae55)
Location: include/net/flow.h:199
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/ip_output.c (ffffffff81e9e014)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6b65)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff81edbc94)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81edd807)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81eeca51)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81f0c0e0)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81f252c5)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/ip_output.c (ffffffff81efc7de)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05342)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff81f3ad64)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81f3ca5e)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81f4b63d)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81f6bd6f)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81f84e56)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/ip_output.c (ffffffff81fc071e)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc96a5)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/datagram.c (ffffffff82000e62)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff82002cd0)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8201174d)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/ping.c (ffffffff8203233f)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/flow.h:178
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff8204b5cd)
Location: include/net/flow.h:178
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
