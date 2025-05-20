# Function: <code>rt6_get_cookie_safe</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff817f9592)
Location: include/net/ip6_fib.h:176
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/ipv6/af_inet6.c (ffffffff81886979)
Location: include/net/ip6_fib.h:176
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff818996cf)
Location: include/net/ip6_fib.h:176
Inline: True
```
```
In net/ipv6/udp.c (ffffffff818a917c)
Location: include/net/ip6_fib.h:176
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7f3d)
Location: include/net/ip6_fib.h:176
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/datagram.c (ffffffff818bc1f4)
Location: include/net/ip6_fib.h:176
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff818bf054)
Location: include/net/ip6_fib.h:176
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c4a37)
Location: include/net/ip6_fib.h:176
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
In net/core/dst_cache.c (ffffffff81876ea2)
Location: include/net/ip6_fib.h:220
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
```
```
In net/ipv6/af_inet6.c (ffffffff81907b69)
Location: include/net/ip6_fib.h:220
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
```
```
In net/ipv6/route.c (ffffffff8191a7bf)
Location: include/net/ip6_fib.h:220
Inline: True
```
```
In net/ipv6/udp.c (ffffffff8192b8a4)
Location: include/net/ip6_fib.h:220
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193adbd)
Location: include/net/ip6_fib.h:220
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/datagram.c (ffffffff8193f2cd)
Location: include/net/ip6_fib.h:220
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81942194)
Location: include/net/ip6_fib.h:220
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819480b0)
Location: include/net/ip6_fib.h:220
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_init_path
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
