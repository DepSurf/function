# Function: <code>l3mdev_master_ifindex_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c24f5)
Location: include/net/l3mdev.h:64
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
```
In net/ipv4/tcp_input.c (ffffffff817dc6b7)
Location: include/net/l3mdev.h:64
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/syncookies.c (ffffffff81819426)
Location: include/net/l3mdev.h:64
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8181c4b3)
Location: include/net/l3mdev.h:64
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186b8a5)
Location: include/net/l3mdev.h:64
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff8186f1a9)
Location: include/net/l3mdev.h:64
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff8180c794)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/syncookies.c (ffffffff8184acaf)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8184dd73)
Location: include/net/l3mdev.h:61
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189e705)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff818a2114)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff8182c932)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/syncookies.c (ffffffff8186e6f3)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff818717c3)
Location: include/net/l3mdev.h:61
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c4dba)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff818c87ab)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/inet_hashtables.c (ffffffff8189d6cd)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/tcp_input.c (ffffffff818ab7f7)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/syncookies.c (ffffffff818ef094)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff818f2183)
Location: include/net/l3mdev.h:61
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81947e3f)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff8194bd7c)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81953383)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff818f247c)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/tcp_input.c (ffffffff81900e19)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/raw.c (ffffffff81919a86)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8191bd6c)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81945a3d)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81948adf)
Location: include/net/l3mdev.h:61
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199352c)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81998587)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a0fa4)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff819a5022)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819acdb6)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81920bca)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922372)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (ffffffff8192ef94)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/raw.c (ffffffff8194829f)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8194a366)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81975d97)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8197a7af)
Location: include/net/l3mdev.h:61
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b4bb6)
Location: include/net/l3mdev.h:61
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c98d3)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819ce8cc)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7bd6)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff819dbac6)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3778)
Location: include/net/l3mdev.h:61
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff819834ab)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81984b36)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (ffffffff81992529)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/raw.c (ffffffff819acd5e)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819aeaaa)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff819df925)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff819e4301)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a23852)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a38392)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a3d574)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46be6)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff81a4a772)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a52484)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff819b9d21)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb5a6)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (ffffffff819c9096)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/raw.c (ffffffff819e3912)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819e57c8)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81a1696a)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a1b311)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a5a1c8)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6eeda)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a741d4)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7d796)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff81a81336)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a89094)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81aa4807)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa7525)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_input.c (ffffffff81ab4578)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac64f9)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
```
```
In net/ipv4/raw.c (ffffffff81ad1209)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ad5586)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81b0799a)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b0c3ca)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b528f4)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69864)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6e4d4)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b78086)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff81b7c011)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b841c4)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81aaee57)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab1bb5)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_input.c (ffffffff81abef07)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad381d)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
```
```
In net/ipv4/raw.c (ffffffff81add1a6)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ae1aea)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81b15d60)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b1a632)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b611cb)
Location: include/net/l3mdev.h:76
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b782ce)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b7cf7b)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b86fc8)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff81b8b042)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93a2b)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81a9a115)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ce24)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_input.c (ffffffff81aab33b)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe8b8)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
```
```
In net/ipv4/raw.c (ffffffff81ac8222)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81acb7dc)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81b03b67)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b082c2)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4f49c)
Location: include/net/l3mdev.h:76
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67217)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6ba5a)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b75c98)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff81b79ea5)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82b3b)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81b55586)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b58b64)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_input.c (ffffffff81b67744)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7c3e8)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
```
```
In net/ipv4/raw.c (ffffffff81b86a90)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81b8a06c)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81bc5e14)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81bcb1d2)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c16775)
Location: include/net/l3mdev.h:76
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2ee10)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81c338ba)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c40708)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff81c44b61)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4ec0b)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81ce3171)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce6da3)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (ffffffff81cf67e5)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0c318)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
```
```
In net/ipv4/raw.c (ffffffff81d174ec)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81d1d936)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81d5b0d5)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81d60ba2)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db20da)
Location: include/net/l3mdev.h:76
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc1f8)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81dd1105)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81dded89)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff81de3b6b)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def5cb)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81ea56fd)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81eaa067)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (ffffffff81ebb1f5)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed1d58)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
```
```
In net/ipv4/raw.c (ffffffff81eddd06)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ee4a2c)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81f25545)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f2b549)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f808e2)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d30a)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81fa24df)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb0e39)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff81fb61eb)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc369b)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81f03e84)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f088d7)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (ffffffff81f19680)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f30a26)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
```
```
In net/ipv4/raw.c (ffffffff81f3cfac)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81f443c8)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81f850d5)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f8af42)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe0df1)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffddd5)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81fff8d4)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff82002d76)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820114e9)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff82016903)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820244db)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81fc8194)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcccd2)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (ffffffff81fdde19)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff6936)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
```
```
In net/ipv4/raw.c (ffffffff82002b16)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8200a360)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff8204ad3c)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
```
```
In net/ipv4/xfrm4_policy.c (ffffffff82052622)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
```
```
In net/ipv4/tcp_ao.c (ffffffff82058eed)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
  - net/ipv4/tcp_ao.c:tcp_ao_connect_init
  - net/ipv4/tcp_ao.c:tcp_ao_syncookie
  - net/ipv4/tcp_ao.c:tcp_v4_ao_lookup
  - net/ipv4/tcp_ao.c:tcp_v4_ao_lookup_rsk
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820af304)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ccc64)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff820ce6a6)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/datagram.c (ffffffff820d1d4d)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e0489)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f37eb)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/ipv6/tcp_ao.c (ffffffff820f4ace)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/tcp_ao.c:tcp_v6_ao_lookup_rsk
  - net/ipv6/tcp_ao.c:tcp_v6_ao_lookup
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
In net/ipv4/inet_hashtables.c (ffff800010c6b608)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6e280)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (ffff800010c7a978)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/raw.c (ffff800010c983ec)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffff800010c9e1e0)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffff800010cd257c)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffff800010cd73a0)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1f814)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d377b0)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffff800010d3cc30)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48960)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffff800010d4ca70)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55ea8)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (c0d7a65c)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (c0d7ce78)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (c0d887b0)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/raw.c (c0da62b8)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c0da8fe0)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (c0ddc3f0)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (c0de1018)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
```
```
In net/ipv6/ipv6_sockglue.c (c0e24588)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (c0e39b18)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c0e3fe8c)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (c0e49fa8)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (c0e4dd70)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (c0e56430)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (c000000000d70af4)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (c000000000d73e54)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (c000000000d855a4)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/raw.c (c000000000da97d8)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c000000000db0210)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (c000000000df0ac0)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (c000000000df72ac)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4da9c)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (c000000000e69de4)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c000000000e70798)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7dd54)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (c000000000e83284)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8ef2c)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffe0007d11ea)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d29a0)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (ffffffe0007de90a)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/raw.c (ffffffe0007f66a4)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffe0007f8090)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffe0008238ee)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffe000827c5c)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe0008612aa)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000874b70)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffe0008791ae)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000882096)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffe0008857ca)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d754)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81959b91)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b416)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (ffffffff81968f06)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/raw.c (ffffffff81983782)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81985638)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff819b5ffa)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff819ba9a1)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f9858)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0e56a)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a13864)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1ce26)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff81a209c6)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a28724)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81913681)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914f06)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (ffffffff819229f6)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/raw.c (ffffffff8193d242)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8193f0f8)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81972dea)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81977791)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b6618)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb32a)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819d0624)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9be6)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff819dd786)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e54e4)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff819c4361)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5be6)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (ffffffff819d36d6)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/raw.c (ffffffff819edf52)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819efe08)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81a2089a)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a25421)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a642d8)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78fea)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a7e2e4)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a878a6)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff81a8b446)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a942d4)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff819cddcc)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf6c7)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_input.c (ffffffff819dd287)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/raw.c (ffffffff819f7f59)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819fa651)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/syncookies.c (ffffffff81a2bda5)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a3088d)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a707da)
Location: include/net/l3mdev.h:57
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a8578d)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a8ab69)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a9447b)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
```
```
In net/ipv6/syncookies.c (ffffffff81a98053)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa0423)
Location: include/net/l3mdev.h:57
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
</details>
</li>
</ul>

## Differences
