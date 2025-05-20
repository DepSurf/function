# Function: <code>security_sk_classify_flow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133b9e0)
Location: security/security.c:1310
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff8133b9e0-ffffffff8133ba21: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81370fa0)
Location: security/security.c:1340
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff81370fa0-ffffffff81370fe1: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813878d0)
Location: security/security.c:1361
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff813878d0-ffffffff81387911: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139c570)
Location: security/security.c:2310
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff8139c570-ffffffff8139c5b1: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c1d00)
Location: security/security.c:2171
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff813c1d00-ffffffff813c1d47: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f32c0)
Location: security/security.c:1471
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff813f32c0-ffffffff813f32ff: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140e690)
Location: security/security.c:2231
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff8140e690-ffffffff8140e6cf: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143b230)
Location: security/security.c:2250
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff8143b230-ffffffff8143b271: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81454fe0)
Location: security/security.c:2289
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff81454fe0-ffffffff8145501f: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a7840)
Location: security/security.c:2612
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_flow_key_init
  - net/ipv6/datagram.c:ip6_datagram_flow_key_init
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff814a7840-ffffffff814a787f: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c4dc0)
Location: security/security.c:2629
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_flow_key_init
  - net/ipv6/datagram.c:ip6_datagram_flow_key_init
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff814c4dc0-ffffffff814c4dff: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cb2b0)
Location: security/security.c:2692
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff814cb2b0-ffffffff814cb2ef: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81523fb0)
Location: security/security.c:2700
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff81523fb0-ffffffff81523fef: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b7e40)
Location: security/security.c:2734
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff815b7e40-ffffffff815b7e89: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816632b0)
Location: security/security.c:2714
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff816632b0-ffffffff816632f9: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169b7b0)
Location: security/security.c:4722
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff8169b7b0-ffffffff8169b7f9: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void security_sk_classify_flow(const struct sock *sk, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d8450)
Location: security/security.c:4913
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff816d8450-ffffffff816d8499: security_sk_classify_flow (STB_GLOBAL)
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
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105402f8)
Location: security/security.c:2289
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffff8000105402f8-ffff800010540350: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f6380)
Location: security/security.c:2289
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
c06f6380-c06f63d0: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000691b60)
Location: security/security.c:2289
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
c000000000691b60-c000000000691bf0: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039d4ae)
Location: security/security.c:2289
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffe00039d4ae-ffffffe00039d4f0: security_sk_classify_flow (STB_GLOBAL)
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
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d5c0)
Location: security/security.c:2289
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff8144d5c0-ffffffff8144d5ff: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e010)
Location: security/security.c:2289
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff8143e010-ffffffff8143e04f: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81449660)
Location: security/security.c:2289
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff81449660-ffffffff8144969f: security_sk_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_sk_classify_flow(struct sock *sk, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81460a30)
Location: security/security.c:2289
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/af_inet6.c:inet6_sk_rebuild_header
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_flow_init
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_socket
```
**Symbols:**

```
ffffffff81460a30-ffffffff81460a6f: security_sk_classify_flow (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct flowi_common *flic</code>
</li>
<li>
<b>Param removed. </b>
<code>struct flowi *fl</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sock *sk</code> ➡️ <code>const struct sock *sk</code>
</li>
</ul>
</details>
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
