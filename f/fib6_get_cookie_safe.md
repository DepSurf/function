# Function: <code>fib6_get_cookie_safe</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff818c85ce)
Location: include/net/ip6_fib.h:232
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/ipv6/af_inet6.c (ffffffff8195e731)
Location: include/net/ip6_fib.h:232
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81977884)
Location: include/net/ip6_fib.h:232
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
```
In net/ipv6/udp.c (ffffffff81986755)
Location: include/net/ip6_fib.h:232
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199384e)
Location: include/net/ip6_fib.h:232
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff8199afe0)
Location: include/net/ip6_fib.h:232
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a112c)
Location: include/net/ip6_fib.h:232
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
In net/core/dst_cache.c (ffffffff818f3505)
Location: include/net/ip6_fib.h:235
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/ipv6/af_inet6.c (ffffffff819932a9)
Location: include/net/ip6_fib.h:235
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff819ad488)
Location: include/net/ip6_fib.h:235
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
```
In net/ipv6/udp.c (ffffffff819bd042)
Location: include/net/ip6_fib.h:235
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c9f62)
Location: include/net/ip6_fib.h:235
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d193d)
Location: include/net/ip6_fib.h:235
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7e51)
Location: include/net/ip6_fib.h:235
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
In net/core/dst_cache.c (ffffffff819459c4)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ec6d7)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff819fed20)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81a1a5fb)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
```
In net/ipv6/udp.c (ffffffff81a2b8aa)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a38b86)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a406e7)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46e47)
Location: include/net/ip6_fib.h:240
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
In net/core/dst_cache.c (ffffffff8197a9e4)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a236d7)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81a35915)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81a5126b)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
```
In net/ipv6/udp.c (ffffffff81a6240d)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6f6f6)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a7735b)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7d9f7)
Location: include/net/ip6_fib.h:240
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
In net/core/dst_cache.c (ffffffff81a4fea1)
Location: include/net/ip6_fib.h:273
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b118a9)
Location: include/net/ip6_fib.h:273
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a7f6)
Location: include/net/ip6_fib.h:273
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81b48990)
Location: include/net/ip6_fib.h:273
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81b5b0fb)
Location: include/net/ip6_fib.h:273
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b695de)
Location: include/net/ip6_fib.h:273
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b715f0)
Location: include/net/ip6_fib.h:273
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b78236)
Location: include/net/ip6_fib.h:273
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
In net/core/dst_cache.c (ffffffff81a55ec8)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b2018d)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81b39185)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81b57584)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81b698e9)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78008)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b8026b)
Location: include/net/ip6_fib.h:274
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b87191)
Location: include/net/ip6_fib.h:274
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
In net/core/dst_cache.c (ffffffff81a38ed8)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0e06f)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81b26e69)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81b45173)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81b57bd6)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66f48)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b6ee6f)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b75e5d)
Location: include/net/ip6_fib.h:275
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
In net/core/dst_cache.c (ffffffff81aeeda8)
Location: include/net/ip6_fib.h:277
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd0c4b)
Location: include/net/ip6_fib.h:277
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81bed15e)
Location: include/net/ip6_fib.h:277
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81c0c2c4)
Location: include/net/ip6_fib.h:277
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81c1f1a8)
Location: include/net/ip6_fib.h:277
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2eb41)
Location: include/net/ip6_fib.h:277
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81c36efd)
Location: include/net/ip6_fib.h:277
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c408d2)
Location: include/net/ip6_fib.h:277
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
In net/core/dst_cache.c (ffffffff81c71d9f)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d67205)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81d85498)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81da71ac)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81dbba8e)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc387)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81dd4a5b)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddef8d)
Location: include/net/ip6_fib.h:278
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
In net/core/dst_cache.c (ffffffff81e29e9f)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f31f0f)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81f52f38)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81f767ac)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81f8bb93)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d4ba)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81fa60e4)
Location: include/net/ip6_fib.h:278
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb11bd)
Location: include/net/ip6_fib.h:278
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
In net/core/dst_cache.c (ffffffff81e9f830)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f91503)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2923)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81fd67c0)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff81fec2f9)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffdb35)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff82006968)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff82011873)
Location: include/net/ip6_fib.h:275
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
In net/core/dst_cache.c (ffffffff81f61fa0)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205f26f)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff820800b3)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff820a4140)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
```
```
In net/ipv6/udp.c (ffffffff820b9f1b)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc9c4)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff820d57c8)
Location: include/net/ip6_fib.h:275
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e0823)
Location: include/net/ip6_fib.h:275
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
In net/core/dst_cache.c (ffff800010c22130)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce07b8)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffff800010cf62f4)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffff800010d151bc)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
```
In net/ipv6/udp.c (ffff800010d27454)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d381bc)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffff800010d409c4)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48c1c)
Location: include/net/ip6_fib.h:240
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
In net/core/dst_cache.c (c0d393f4)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (c0de9bac)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (c0dfce18)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (c0e1ae60)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
```
In net/ipv6/udp.c (c0e2c394)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3b474)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (c0e43398)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (c0e49e98)
Location: include/net/ip6_fib.h:240
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
In net/core/dst_cache.c (c000000000d14448)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (c000000000e02b9c)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (c000000000e1c8d8)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (c000000000e42110)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
```
In net/ipv6/udp.c (c000000000e583bc)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b8ec)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (c000000000e75038)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7dc14)
Location: include/net/ip6_fib.h:240
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
In net/core/dst_cache.c (ffffffe00079ab94)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f538)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffe000841baa)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffe00085a8b4)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
```
In net/ipv6/udp.c (ffffffe000869124)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087539c)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffe00087c284)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000881fa2)
Location: include/net/ip6_fib.h:240
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
In net/core/dst_cache.c (ffffffff8191a854)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c2d67)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff819d4fa5)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff819f08fb)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
```
In net/ipv6/udp.c (ffffffff81a01a9d)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ed86)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a169eb)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1d087)
Location: include/net/ip6_fib.h:240
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
In net/core/dst_cache.c (ffffffff818d4604)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fb57)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81991d65)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff819ad6bb)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
```
In net/ipv6/udp.c (ffffffff819be85d)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbb46)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d37ab)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9e47)
Location: include/net/ip6_fib.h:240
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
In net/core/dst_cache.c (ffffffff8196b9e4)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2d7e7)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81a3fa25)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81a5b37b)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
```
In net/ipv6/udp.c (ffffffff81a6c51d)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a79806)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a8146b)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a87b07)
Location: include/net/ip6_fib.h:240
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
In net/core/dst_cache.c (ffffffff8198de5c)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a38fce)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/af_inet6.c (ffffffff81a4b558)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff81a67673)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
```
```
In net/ipv6/udp.c (ffffffff81a78b44)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a85fe8)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a8dd4b)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a9470e)
Location: include/net/ip6_fib.h:240
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
</details>
</li>
</ul>

## Differences
