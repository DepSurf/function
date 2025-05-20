# Function: <code>sock_i_uid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817002e0)
Location: net/core/sock.c:1721
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
  - net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict
  - net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff817002e0-ffffffff81700332: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81766db0)
Location: net/core/sock.c:1750
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
  - net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict
  - net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff81766db0-ffffffff81766e02: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81793e30)
Location: net/core/sock.c:1748
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
  - net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict
  - net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff81793e30-ffffffff81793e82: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b2200)
Location: net/core/sock.c:1887
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff817b2200-ffffffff817b2242: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182a390)
Location: net/core/sock.c:1898
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff8182a390-ffffffff8182a3d2: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81874500)
Location: net/core/sock.c:1918
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff81874500-ffffffff81874542: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81894dd0)
Location: net/core/sock.c:1914
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff81894dd0-ffffffff81894e12: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818df260)
Location: net/core/sock.c:2055
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff818df260-ffffffff818df2a8: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81911430)
Location: net/core/sock.c:2068
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff81911430-ffffffff81911478: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e3280)
Location: net/core/sock.c:2177
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_openreq4
  - net/ipv4/raw.c:raw_sock_seq_show
  - net/ipv4/udp.c:udp4_format_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_format_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_openreq6
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff819e3280-ffffffff819e32c8: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e2e70)
Location: net/core/sock.c:2169
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_openreq4
  - net/ipv4/raw.c:raw_sock_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_format_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_format_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_openreq6
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff819e2e70-ffffffff819e2eb8: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819c8e90)
Location: net/core/sock.c:2192
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff819c8e90-ffffffff819c8ed8: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a78230)
Location: net/core/sock.c:2316
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff81a78230-ffffffff81a78278: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81beb840)
Location: net/core/sock.c:2483
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff81beb840-ffffffff81beb887: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d98230)
Location: net/core/sock.c:2562
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_bind_conflict
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff81d98230-ffffffff81d98277: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e068a0)
Location: net/core/sock.c:2611
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_bind_conflict
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff81e068a0-ffffffff81e068e7: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec3190)
Location: net/core/sock.c:2591
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_bind_conflict
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff81ec3190-ffffffff81ec31d7: sock_i_uid (STB_GLOBAL)
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
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bab980)
Location: net/core/sock.c:2068
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffff800010bab980-ffff800010baba74: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc7710)
Location: net/core/sock.c:2068
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
c0cc7710-c0cc7754: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7de20)
Location: net/core/sock.c:2068
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
c000000000c7de20-c000000000c7de8c: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073c39a)
Location: net/core/sock.c:2068
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffe00073c39a-ffffffe00073c3e4: sock_i_uid (STB_GLOBAL)
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
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b1430)
Location: net/core/sock.c:2068
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff818b1430-ffffffff818b1478: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186b380)
Location: net/core/sock.c:2068
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff8186b380-ffffffff8186b3c8: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81902430)
Location: net/core/sock.c:2068
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff81902430-ffffffff81902478: sock_i_uid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
kuid_t sock_i_uid(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819233d0)
Location: net/core/sock.c:2068
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/udp.c:udp_lib_lport_inuse
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/packet/af_packet.c:packet_seq_show
```
**Symbols:**

```
ffffffff819233d0-ffffffff81923418: sock_i_uid (STB_GLOBAL)
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
