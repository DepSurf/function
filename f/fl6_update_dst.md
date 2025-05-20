# Function: <code>fl6_update_dst</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff817f2af0)
Location: net/ipv6/exthdrs.c:864
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff817f2af0-ffffffff817f2b31: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81861870)
Location: net/ipv6/exthdrs.c:940
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81861870-ffffffff818618b1: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff818937c0)
Location: net/ipv6/exthdrs.c:1156
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff818937c0-ffffffff8189382d: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff818b9d80)
Location: net/ipv6/exthdrs.c:1158
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff818b9d80-ffffffff818b9df9: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff8193cd00)
Location: net/ipv6/exthdrs.c:1208
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8193cd00-ffffffff8193cd79: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81995d60)
Location: net/ipv6/exthdrs.c:1144
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81995d60-ffffffff81995dcc: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff819cc670)
Location: net/ipv6/exthdrs.c:1144
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819cc670-ffffffff819cc6de: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a3b170)
Location: net/ipv6/exthdrs.c:1140
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81a3b170-ffffffff81a3b1de: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a71df0)
Location: net/ipv6/exthdrs.c:1140
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81a71df0-ffffffff81a71e5e: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b6b6f0)
Location: net/ipv6/exthdrs.c:1337
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81b6b6f0-ffffffff81b6b75e: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b7a180)
Location: net/ipv6/exthdrs.c:1331
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81b7a180-ffffffff81b7a1ee: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b68ca0)
Location: net/ipv6/exthdrs.c:1331
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81b68ca0-ffffffff81b68d1d: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81c30960)
Location: net/ipv6/exthdrs.c:1379
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81c30960-ffffffff81c309dd: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81dce0e0)
Location: net/ipv6/exthdrs.c:1380
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81dce0e0-ffffffff81dce18b: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81f9f330)
Location: net/ipv6/exthdrs.c:1380
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81f9f330-ffffffff81f9f3db: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81fffea0)
Location: net/ipv6/exthdrs.c:1347
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81fffea0-ffffffff81ffff34: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff820cec30)
Location: net/ipv6/exthdrs.c:1352
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff820cec30-ffffffff820cecc4: fl6_update_dst (STB_GLOBAL)
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
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffff800010d3a780)
Location: net/ipv6/exthdrs.c:1140
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffff800010d3a780-ffff800010d3a824: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (c0e3ccc4)
Location: net/ipv6/exthdrs.c:1140
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c0e3ccc4-c0e3cd58: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (c000000000e6dac0)
Location: net/ipv6/exthdrs.c:1140
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c000000000e6dac0-c000000000e6db58: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffe000877400)
Location: net/ipv6/exthdrs.c:1140
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffe000877400-ffffffe0008774ac: fl6_update_dst (STB_GLOBAL)
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
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a11480)
Location: net/ipv6/exthdrs.c:1140
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81a11480-ffffffff81a114ee: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff819ce240)
Location: net/ipv6/exthdrs.c:1140
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819ce240-ffffffff819ce2ae: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a7bf00)
Location: net/ipv6/exthdrs.c:1140
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81a7bf00-ffffffff81a7bf6e: fl6_update_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct in6_addr *fl6_update_dst(struct flowi6 *fl6, const struct ipv6_txoptions *opt, struct in6_addr *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a88750)
Location: net/ipv6/exthdrs.c:1140
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81a88750-ffffffff81a887be: fl6_update_dst (STB_GLOBAL)
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
