# Function: <code>ip6_dst_store</code>

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
In net/ipv6/af_inet6.c (ffffffff817c368a)
Location: include/net/ip6_route.h:144
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff817e22a2)
Location: include/net/ip6_route.h:144
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817effc3)
Location: include/net/ip6_route.h:144
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff817f4261)
Location: include/net/ip6_route.h:144
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff817f75c6)
Location: include/net/ip6_route.h:144
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff8183073a)
Location: include/net/ip6_route.h:164
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff81850b4a)
Location: include/net/ip6_route.h:164
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185faac)
Location: include/net/ip6_route.h:164
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81863615)
Location: include/net/ip6_route.h:164
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81866716)
Location: include/net/ip6_route.h:164
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff818621c4)
Location: include/net/ip6_route.h:169
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff81882999)
Location: include/net/ip6_route.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81891a0c)
Location: include/net/ip6_route.h:169
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81895c2f)
Location: include/net/ip6_route.h:169
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81898e11)
Location: include/net/ip6_route.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff8188694f)
Location: include/net/ip6_route.h:170
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff818a914a)
Location: include/net/ip6_route.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7ee8)
Location: include/net/ip6_route.h:170
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff818bc1ac)
Location: include/net/ip6_route.h:170
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff818bf028)
Location: include/net/ip6_route.h:170
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff81907b3f)
Location: include/net/ip6_route.h:187
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff8192b871)
Location: include/net/ip6_route.h:187
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193ad68)
Location: include/net/ip6_route.h:187
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff8193f285)
Location: include/net/ip6_route.h:187
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81942168)
Location: include/net/ip6_route.h:187
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff8195e700)
Location: include/net/ip6_route.h:206
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff8197785e)
Location: include/net/ip6_route.h:206
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993819)
Location: include/net/ip6_route.h:206
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff8199af9a)
Location: include/net/ip6_route.h:206
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff81993276)
Location: include/net/ip6_route.h:206
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff819ad45e)
Location: include/net/ip6_route.h:206
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c9f29)
Location: include/net/ip6_route.h:206
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d18f6)
Location: include/net/ip6_route.h:206
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff819fecf9)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81a1a5de)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a38b5c)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a406c1)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff81a358ee)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81a5124e)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6f6cc)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a77335)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff81b2a7ca)
Location: include/net/ip6_route.h:227
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81b4896e)
Location: include/net/ip6_route.h:227
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b695ae)
Location: include/net/ip6_route.h:227
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b715c3)
Location: include/net/ip6_route.h:227
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff81b39152)
Location: include/net/ip6_route.h:227
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81b57560)
Location: include/net/ip6_route.h:227
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b77fd8)
Location: include/net/ip6_route.h:227
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b80238)
Location: include/net/ip6_route.h:227
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff81b26e36)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81b4514e)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66f18)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b6ee3c)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff81bed122)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81c0c28c)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2eb08)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81c36ec1)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff81d8545a)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81da7130)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcbf3d)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81dd4a1b)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff81f52efa)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81f76730)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d055)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81fa60a4)
Location: include/net/ip6_route.h:228
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff81fb28df)
Location: include/net/ip6_route.h:224
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81fd6741)
Location: include/net/ip6_route.h:224
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffdae5)
Location: include/net/ip6_route.h:224
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff82006922)
Location: include/net/ip6_route.h:224
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff8208006f)
Location: include/net/ip6_route.h:223
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff820a40c1)
Location: include/net/ip6_route.h:223
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc976)
Location: include/net/ip6_route.h:223
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff820d5782)
Location: include/net/ip6_route.h:223
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffff800010cf62cc)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffff800010d151a4)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38194)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffff800010d4099c)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (c0dfcdf8)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (c0e1ae4c)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (c0e3b45c)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (c0e43378)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (c000000000e1c8a8)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (c000000000e420dc)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b8c0)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (c000000000e75008)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffe000841b8c)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffe00085a890)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875372)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffe00087c266)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff819d4f7e)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff819f08de)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ed5c)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a169c5)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff81991d3e)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff819ad69e)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbb1c)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d3785)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff81a3f9fe)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81a5b35e)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a797dc)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a81445)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
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
In net/ipv6/af_inet6.c (ffffffff81a4b52b)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81a67650)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a85fac)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a8dd1f)
Location: include/net/ip6_route.h:226
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
</details>
</li>
</ul>

## Differences
