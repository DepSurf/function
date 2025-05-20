# Function: <code>sk_setup_caps</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81700890)
Location: net/core/sock.c:1604
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff81700890-ffffffff81700971: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81767250)
Location: net/core/sock.c:1609
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff81767250-ffffffff81767335: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817942d0)
Location: net/core/sock.c:1607
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff817942d0-ffffffff817943b5: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b26a0)
Location: net/core/sock.c:1750
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff817b26a0-ffffffff817b2789: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182a860)
Location: net/core/sock.c:1761
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff8182a860-ffffffff8182a991: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818749c0)
Location: net/core/sock.c:1781
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff818749c0-ffffffff81874af4: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818951d0)
Location: net/core/sock.c:1777
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff818951d0-ffffffff81895306: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818df700)
Location: net/core/sock.c:1909
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff818df700-ffffffff818df83b: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819118d0)
Location: net/core/sock.c:1922
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff819118d0-ffffffff81911a0b: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e3710)
Location: net/core/sock.c:2019
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff819e3710-ffffffff819e3846: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e3260)
Location: net/core/sock.c:2011
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff819e3260-ffffffff819e339b: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819c92b0)
Location: net/core/sock.c:2040
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff819c92b0-ffffffff819c93e5: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a78650)
Location: net/core/sock.c:2164
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff81a78650-ffffffff81a78785: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bebf70)
Location: net/core/sock.c:2312
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff81bebf70-ffffffff81bec142: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d98940)
Location: net/core/sock.c:2391
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff81d98940-ffffffff81d98b12: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e08130)
Location: net/core/sock.c:2443
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff81e08130-ffffffff81e082e0: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec4b70)
Location: net/core/sock.c:2423
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff81ec4b70-ffffffff81ec4d4f: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010ba9560)
Location: net/core/sock.c:1922
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffff800010ba9560-ffff800010ba9678: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cca554)
Location: net/core/sock.c:1922
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
c0cca554-c0cca6bc: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7e560)
Location: net/core/sock.c:1922
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
c000000000c7e560-c000000000c7e6f8: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073c904)
Location: net/core/sock.c:1922
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffe00073c904-ffffffe00073ca02: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b18d0)
Location: net/core/sock.c:1922
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff818b18d0-ffffffff818b1a0b: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186b820)
Location: net/core/sock.c:1922
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff8186b820-ffffffff8186b95b: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819028d0)
Location: net/core/sock.c:1922
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff819028d0-ffffffff81902a0b: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sk_setup_caps(struct sock *sk, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81923870)
Location: net/core/sock.c:1922
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff81923870-ffffffff819239ab: sk_setup_caps (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
