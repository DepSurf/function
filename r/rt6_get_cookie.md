# Function: <code>rt6_get_cookie</code>

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
In net/ipv6/af_inet6.c (ffffffff817c36a7)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff817e22c3)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817efff9)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff817f4282)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff817f75e5)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fbd98)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_init_path
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
In net/core/dst_cache.c (ffffffff817aae35)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/ipv6/af_inet6.c (ffffffff81830757)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff81850b6a)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185fad6)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/datagram.c (ffffffff81863636)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81866735)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186b668)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_init_path
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
In net/core/dst_cache.c (ffffffff817da455)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/ipv6/af_inet6.c (ffffffff818621e1)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff818829b9)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81891a36)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/datagram.c (ffffffff81895c50)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81898e30)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189e4c8)
Location: include/net/ip6_fib.h:168
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_init_path
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
In net/core/dst_cache.c (ffffffff817f956b)
Location: include/net/ip6_fib.h:194
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/ipv6/af_inet6.c (ffffffff8188696c)
Location: include/net/ip6_fib.h:194
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff818a916a)
Location: include/net/ip6_fib.h:194
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7f15)
Location: include/net/ip6_fib.h:194
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/datagram.c (ffffffff818bc1cd)
Location: include/net/ip6_fib.h:194
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff818bf047)
Location: include/net/ip6_fib.h:194
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c4a10)
Location: include/net/ip6_fib.h:194
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_init_path
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
In net/core/dst_cache.c (ffffffff81876e7b)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/ipv6/af_inet6.c (ffffffff81907b5c)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/udp.c (ffffffff8192b892)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193ad95)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/datagram.c (ffffffff8193f2a6)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81942187)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8194809f)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_init_path
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
In net/core/dst_cache.c (ffffffff818c85b9)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/ipv6/af_inet6.c (ffffffff8195e71d)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81977870)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff819864a9)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993835)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff8199afb9)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a1114)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_init_path
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
In net/core/dst_cache.c (ffffffff818f34e9)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/ipv6/af_inet6.c (ffffffff81993290)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff819ad470)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff819bcd96)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c9f45)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d1912)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7e34)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_init_path
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
In net/core/dst_cache.c (ffffffff819459b8)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ec6cc)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff819fed15)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81a1a5f0)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81a2b89f)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a38b7b)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a406db)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46e3c)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffff8197a9d8)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a236cc)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81a3590a)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81a51260)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81a62402)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6f6eb)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a7734f)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7d9ec)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffff81a4fe8b)
Location: include/net/ip6_fib.h:291
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11898)
Location: include/net/ip6_fib.h:291
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a7e6)
Location: include/net/ip6_fib.h:291
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81b48980)
Location: include/net/ip6_fib.h:291
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81b5b0eb)
Location: include/net/ip6_fib.h:291
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b695cd)
Location: include/net/ip6_fib.h:291
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b715dd)
Location: include/net/ip6_fib.h:291
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b78226)
Location: include/net/ip6_fib.h:291
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffff81a55eb3)
Location: include/net/ip6_fib.h:292
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b20179)
Location: include/net/ip6_fib.h:292
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81b3916e)
Location: include/net/ip6_fib.h:292
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81b57573)
Location: include/net/ip6_fib.h:292
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81b698d5)
Location: include/net/ip6_fib.h:292
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b77ff7)
Location: include/net/ip6_fib.h:292
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b80252)
Location: include/net/ip6_fib.h:292
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b8717b)
Location: include/net/ip6_fib.h:292
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffff81a38ec3)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0e05b)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81b26e52)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81b45162)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81b57bbe)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66f37)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b6ee56)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b75e47)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffff81aeed93)
Location: include/net/ip6_fib.h:295
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd0c37)
Location: include/net/ip6_fib.h:295
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81bed147)
Location: include/net/ip6_fib.h:295
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81c0c2b3)
Location: include/net/ip6_fib.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81c1f192)
Location: include/net/ip6_fib.h:295
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2eb30)
Location: include/net/ip6_fib.h:295
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81c36ee4)
Location: include/net/ip6_fib.h:295
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c408bc)
Location: include/net/ip6_fib.h:295
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffff81c71d23)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d671e5)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81d8547c)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81da7155)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81dbba34)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcbf61)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81dd4a40)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddef6f)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffff81e29e23)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f31ef2)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81f52f1c)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81f76755)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81f8bb39)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d079)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81fa60c9)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb119f)
Location: include/net/ip6_fib.h:296
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffff81e9f7d5)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f914e5)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2901)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81fd6763)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81fec25c)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffdb0b)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff82006947)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8201184f)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffff81f61f45)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205f251)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff82080091)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff820a40e3)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff820b9ea1)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc99c)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff820d57a7)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e07ff)
Location: include/net/ip6_fib.h:293
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffff800010c22124)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce07ac)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffff800010cf62e8)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffff800010d151b0)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffff800010d27448)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d381b0)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffff800010d409b8)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48c10)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (c0d393e8)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (c0de9ba0)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (c0dfce0c)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (c0e1ae54)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (c0e2c388)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3b468)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (c0e4338c)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (c0e49e8c)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (c000000000d14438)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (c000000000e02b8c)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (c000000000e1c8c8)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (c000000000e42100)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (c000000000e583ac)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b8dc)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (c000000000e75028)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7dc04)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffe00079ab8c)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f530)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffe000841ba4)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffe00085a8ac)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffe00086911c)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875394)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffe00087c27e)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000881f9c)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffff8191a848)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c2d5c)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff819d4f9a)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff819f08f0)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81a01a92)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ed7b)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a169df)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1d07c)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffff818d45f8)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fb4c)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81991d5a)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff819ad6b0)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff819be852)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbb3b)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d379f)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9e3c)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffff8196b9d8)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2d7dc)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81a3fa1a)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81a5b370)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81a6c512)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a797fb)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a8145f)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a87afc)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
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
In net/core/dst_cache.c (ffffffff8198de4b)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a38fba)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81a4b547)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81a67663)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81a78b30)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a85fd8)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a8dd39)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a94700)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
</details>
</li>
</ul>

## Differences
