# Function: <code>flowi6_to_flowi_common</code>

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
In net/ipv6/af_inet6.c (ffffffff81b39118)
Location: include/net/flow.h:208
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff81b6730d)
Location: include/net/flow.h:208
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b6b51a)
Location: include/net/flow.h:208
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81b6e3a3)
Location: include/net/flow.h:208
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b768f4)
Location: include/net/flow.h:208
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81b79d54)
Location: include/net/flow.h:208
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b7c997)
Location: include/net/flow.h:208
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_flow_key_init
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b801c6)
Location: include/net/flow.h:208
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/syncookies.c (ffffffff81b8ae2f)
Location: include/net/flow.h:208
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/af_inet6.c (ffffffff81b26dfc)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff81b55446)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b59863)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81b5c783)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b65272)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81b68881)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6bbc5)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b6edca)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/syncookies.c (ffffffff81b79c92)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/af_inet6.c (ffffffff81bed0e6)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff81c1df1f)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81c20e8c)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81c23fd3)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d4c6)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81c3054b)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81c33a38)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81c36e4d)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/syncookies.c (ffffffff81c4493c)
Location: include/net/flow.h:205
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/af_inet6.c (ffffffff81d8541a)
Location: include/net/flow.h:209
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff81dba590)
Location: include/net/flow.h:209
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81dbdc3f)
Location: include/net/flow.h:209
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81dc0e63)
Location: include/net/flow.h:209
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca8c5)
Location: include/net/flow.h:209
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81dcdd1e)
Location: include/net/flow.h:209
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81dd12aa)
Location: include/net/flow.h:209
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81dd4996)
Location: include/net/flow.h:209
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/syncookies.c (ffffffff81de394d)
Location: include/net/flow.h:209
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/af_inet6.c (ffffffff81f52eba)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff81f8a658)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81f8e15e)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81f91563)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b92b)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81f9ef16)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff81fa28a3)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81fa6013)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/syncookies.c (ffffffff81fb5fcd)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/af_inet6.c (ffffffff81fb28a1)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff81fe9d41)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81fee940)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff81ff1e73)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffbce6)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81fffa4f)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff82003146)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff82006884)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/syncookies.c (ffffffff820166e6)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv6/af_inet6.c (ffffffff82080031)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff820b7fcc)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff820bc509)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (ffffffff820bfa73)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ca3f9)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff820ce84a)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff820d1f17)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff820d56e4)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
```
```
In net/ipv6/syncookies.c (ffffffff820e5708)
Location: include/net/flow.h:188
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
