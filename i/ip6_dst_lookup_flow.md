# Function: <code>ip6_dst_lookup_flow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff817c4680)
Location: net/ipv6/ip6_output.c:1039
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff817c4680-ffffffff817c4743: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff818317f0)
Location: net/ipv6/ip6_output.c:1046
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff818317f0-ffffffff818318b3: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81863250)
Location: net/ipv6/ip6_output.c:1075
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81863250-ffffffff818632ea: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81887a50)
Location: net/ipv6/ip6_output.c:1070
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81887a50-ffffffff81887aed: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81908d00)
Location: net/ipv6/ip6_output.c:1089
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81908d00-ffffffff81908d9d: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8195fed0)
Location: net/ipv6/ip6_output.c:1071
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8195fed0-ffffffff8195ff6a: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81994c60)
Location: net/ipv6/ip6_output.c:1080
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81994c60-ffffffff81994cfa: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a00850)
Location: net/ipv6/ip6_output.c:1144
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81a00850-ffffffff81a008e8: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a37420)
Location: net/ipv6/ip6_output.c:1147
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81a37420-ffffffff81a374b8: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2c940)
Location: net/ipv6/ip6_output.c:1148
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81b2c940-ffffffff81b2c9d8: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3b350)
Location: net/ipv6/ip6_output.c:1187
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81b3b350-ffffffff81b3b3e8: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b29110)
Location: net/ipv6/ip6_output.c:1218
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81b29110-ffffffff81b291a8: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81bf0280)
Location: net/ipv6/ip6_output.c:1197
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81bf0280-ffffffff81bf0318: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81d88920)
Location: net/ipv6/ip6_output.c:1219
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81d88920-ffffffff81d889c5: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81f56710)
Location: net/ipv6/ip6_output.c:1237
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81f56710-ffffffff81f567b5: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81fb6110)
Location: net/ipv6/ip6_output.c:1238
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81fb6110-ffffffff81fb61b5: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff820837d0)
Location: net/ipv6/ip6_output.c:1247
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff820837d0-ffffffff82083875: ip6_dst_lookup_flow (STB_GLOBAL)
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
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cf9fd8)
Location: net/ipv6/ip6_output.c:1147
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffff800010cf9fd8-ffff800010cfa088: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0dfe928)
Location: net/ipv6/ip6_output.c:1147
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c0dfe928-c0dfe9d0: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e1eea0)
Location: net/ipv6/ip6_output.c:1147
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c000000000e1eea0-c000000000e1ef80: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe0008434a8)
Location: net/ipv6/ip6_output.c:1147
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffe0008434a8-ffffffe000843522: ip6_dst_lookup_flow (STB_GLOBAL)
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
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819d6ab0)
Location: net/ipv6/ip6_output.c:1147
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819d6ab0-ffffffff819d6b48: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81993870)
Location: net/ipv6/ip6_output.c:1147
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81993870-ffffffff81993908: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a41530)
Location: net/ipv6/ip6_output.c:1147
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81a41530-ffffffff81a415c8: ip6_dst_lookup_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_flow(struct net *net, const struct sock *sk, struct flowi6 *fl6, const struct in6_addr *final_dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a4d190)
Location: net/ipv6/ip6_output.c:1147
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81a4d190-ffffffff81a4d228: ip6_dst_lookup_flow (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, fl6, final_dst</code> ➡️ <code>net, sk, fl6, final_dst</code>
</li>
</ul>
</details>
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
