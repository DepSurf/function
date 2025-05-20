# Function: <code>ipv6_addr_v4mapped</code>

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
In lib/vsprintf.c (ffffffff813f2b2c)
Location: include/net/ipv6.h:591
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/net/ipv6.h:591
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/net/ipv6.h:591
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781c77)
Location: include/net/ipv6.h:591
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/net/ipv6.h:591
Inline: True
```
```
In net/ipv6/udp.c (ffffffff817e34dd)
Location: include/net/ipv6.h:591
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/net/ipv6.h:591
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/net/ipv6.h:591
Inline: True
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
In lib/vsprintf.c (ffffffff8143a3af)
Location: include/net/ipv6.h:623
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cc9c0)
Location: include/net/ipv6.h:623
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cec3c)
Location: include/net/ipv6.h:623
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ef83b)
Location: include/net/ipv6.h:623
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/route.c (ffffffff81845691)
Location: include/net/ipv6.h:623
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184bd5d)
Location: include/net/ipv6.h:623
Inline: True
```
```
In net/ipv6/udp.c (ffffffff818504ec)
Location: include/net/ipv6.h:623
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185e67d)
Location: include/net/ipv6.h:623
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/datagram.c (ffffffff8186395e)
Location: include/net/ipv6.h:623
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_connect
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
In lib/vsprintf.c (ffffffff8145738f)
Location: include/net/ipv6.h:623
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fc6c0)
Location: include/net/ipv6.h:623
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fea4c)
Location: include/net/ipv6.h:623
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8182024b)
Location: include/net/ipv6.h:623
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81863037)
Location: include/net/ipv6.h:623
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81877428)
Location: include/net/ipv6.h:623
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187dc2f)
Location: include/net/ipv6.h:623
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81882319)
Location: include/net/ipv6.h:623
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818907bd)
Location: include/net/ipv6.h:623
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81895fdf)
Location: include/net/ipv6.h:623
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/ip_sockglue.c (ffffffff8181ca4a)
Location: include/net/ipv6.h:624
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181efc6)
Location: include/net/ipv6.h:624
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183f601)
Location: include/net/ipv6.h:624
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81887908)
Location: include/net/ipv6.h:624
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff8189c728)
Location: include/net/ipv6.h:624
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a3248)
Location: include/net/ipv6.h:624
Inline: True
```
```
In net/ipv6/udp.c (ffffffff818a8b98)
Location: include/net/ipv6.h:624
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b6cd9)
Location: include/net/ipv6.h:624
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff818bc566)
Location: include/net/ipv6.h:624
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In lib/vsprintf.c (ffffffff818f8c54)
Location: include/net/ipv6.h:624
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/ipv4/ip_sockglue.c (ffffffff8189b996)
Location: include/net/ipv6.h:665
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189df76)
Location: include/net/ipv6.h:665
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf8e1)
Location: include/net/ipv6.h:665
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81908bb8)
Location: include/net/ipv6.h:665
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff8191c78a)
Location: include/net/ipv6.h:665
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81925dfd)
Location: include/net/ipv6.h:665
Inline: True
```
```
In net/ipv6/udp.c (ffffffff8192b65e)
Location: include/net/ipv6.h:665
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81939b09)
Location: include/net/ipv6.h:665
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff8193f673)
Location: include/net/ipv6.h:665
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In lib/vsprintf.c (ffffffff8197f724)
Location: include/net/ipv6.h:665
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/ipv4/ip_sockglue.c (ffffffff818eff18)
Location: include/net/ipv6.h:637
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2926)
Location: include/net/ipv6.h:637
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190da8e)
Location: include/net/ipv6.h:637
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff819154b9)
Location: include/net/ipv6.h:637
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff8195fd65)
Location: include/net/ipv6.h:637
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81974cfa)
Location: include/net/ipv6.h:637
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197eafd)
Location: include/net/ipv6.h:637
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819839d2)
Location: include/net/ipv6.h:637
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81991db9)
Location: include/net/ipv6.h:637
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff8199848b)
Location: include/net/ipv6.h:637
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ac9f7)
Location: include/net/ipv6.h:637
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (ffffffff819db951)
Location: include/net/ipv6.h:637
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/ipv4/ip_sockglue.c (ffffffff8191d808)
Location: include/net/ipv6.h:629
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff81920396)
Location: include/net/ipv6.h:629
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193bec4)
Location: include/net/ipv6.h:629
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943c69)
Location: include/net/ipv6.h:629
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81994b04)
Location: include/net/ipv6.h:629
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff819aa942)
Location: include/net/ipv6.h:629
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b5091)
Location: include/net/ipv6.h:629
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819b9f09)
Location: include/net/ipv6.h:629
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8609)
Location: include/net/ipv6.h:629
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819cee54)
Location: include/net/ipv6.h:629
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3421)
Location: include/net/ipv6.h:629
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (ffffffff81a13c41)
Location: include/net/ipv6.h:629
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/ipv4/ip_sockglue.c (ffffffff8197fb88)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982cb6)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a02ea)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a809a)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81a006fb)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81a17d9e)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a2359e)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a29058)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a36fb7)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a3db41)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a520c1)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (ffffffff81a8325f)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/ipv4/ip_sockglue.c (ffffffff819b6528)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b9516)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d6eaa)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de38a)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81a372cb)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/ip6_input.c (ffffffff81a3bda7)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4e9ee)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a5a373)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a5fbb6)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6db67)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a747b1)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a88cc4)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (ffffffff81aba4cf)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In lib/vsprintf.c (ffffffff815f47ce)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa0d7b)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa4056)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac6d82)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc5db)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c7fb)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/ip6_input.c (ffffffff81b3123c)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffff81b4631e)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b525fc)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b586ab)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66777)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6e971)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83d52)
Location: include/net/ipv6.h:687
Inline: True
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
In lib/vsprintf.c (ffffffff81618e3e)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aab33c)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aae685)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad20a2)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad85ab)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b1da)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/route.c (ffffffff81b54e5d)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b615e2)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b66ceb)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b7590b)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b7d41d)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b935b2)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81bc137c)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
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
In lib/vsprintf.c (ffffffff815fc4be)
Location: include/net/ipv6.h:688
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9655c)
Location: include/net/ipv6.h:688
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99765)
Location: include/net/ipv6.h:688
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abd1dd)
Location: include/net/ipv6.h:688
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac3345)
Location: include/net/ipv6.h:688
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81b28fbe)
Location: include/net/ipv6.h:688
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b428ed)
Location: include/net/ipv6.h:688
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4f8b3)
Location: include/net/ipv6.h:688
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b54ec1)
Location: include/net/ipv6.h:688
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6433b)
Location: include/net/ipv6.h:688
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6c001)
Location: include/net/ipv6.h:688
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b826d0)
Location: include/net/ipv6.h:688
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81bb3b40)
Location: include/net/ipv6.h:688
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_info2sockaddr
  - net/mptcp/subflow.c:subflow_v6_conn_request
```
```
In net/mptcp/pm_netlink.c (ffffffff81bba71c)
Location: include/net/ipv6.h:688
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:addresses_equal
  - net/mptcp/pm_netlink.c:addresses_equal
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
In lib/vsprintf.c (ffffffff81669b0b)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b519cc)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54be5)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7b2fd)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b81835)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81bf0076)
Location: include/net/ipv6.h:691
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c0804a)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c16c0f)
Location: include/net/ipv6.h:691
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1d99a)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2bc38)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81c33e9a)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e7a0)
Location: include/net/ipv6.h:691
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81c82290)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_info2sockaddr
  - net/mptcp/subflow.c:subflow_v6_conn_request
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8a6fc)
Location: include/net/ipv6.h:691
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:addresses_equal
  - net/mptcp/pm_netlink.c:addresses_equal
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
In lib/vsprintf.c (ffffffff8178370d)
Location: include/net/ipv6.h:745
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
```
```
In net/core/sock.c (ffffffff81bec126)
Location: include/net/ipv6.h:745
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdf591)
Location: include/net/ipv6.h:745
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce27d5)
Location: include/net/ipv6.h:745
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0aa29)
Location: include/net/ipv6.h:745
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d11c69)
Location: include/net/ipv6.h:745
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81d88706)
Location: include/net/ipv6.h:745
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da2d71)
Location: include/net/ipv6.h:745
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db2406)
Location: include/net/ipv6.h:745
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81db9f60)
Location: include/net/ipv6.h:745
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc994a)
Location: include/net/ipv6.h:745
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81dd173d)
Location: include/net/ipv6.h:745
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def0b2)
Location: include/net/ipv6.h:745
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81e27fb4)
Location: include/net/ipv6.h:745
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_info2sockaddr
  - net/mptcp/subflow.c:subflow_v6_conn_request
```
```
In net/mptcp/pm_netlink.c (ffffffff81e30d44)
Location: include/net/ipv6.h:745
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_addresses_equal
  - net/mptcp/pm_netlink.c:mptcp_addresses_equal
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
In net/core/sock.c (ffffffff81d98af6)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9fa61)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea3c2e)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5d5c)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81eaa30d)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed02d9)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed7a39)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81f564e6)
Location: include/net/ipv6.h:778
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f72161)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f80f9d)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/udp.c (ffffffff81f8a010)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9a8ea)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81fa2d5d)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3152)
Location: include/net/ipv6.h:778
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81ffff04)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_info2sockaddr
  - net/mptcp/subflow.c:subflow_v6_conn_request
```
```
In net/mptcp/pm.c (ffffffff82005bfb)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_addr_families_match
  - net/mptcp/pm.c:mptcp_pm_addr_families_match
```
```
In net/mptcp/pm_netlink.c (ffffffff82009394)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_addresses_equal
  - net/mptcp/pm_netlink.c:mptcp_addresses_equal
```
```
In lib/vsprintf.c (ffffffff8204063d)
Location: include/net/ipv6.h:778
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/core/sock.c (ffffffff81e082c9)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe242)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f024ae)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f044cd)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f08b2e)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2ef89)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f36699)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5ec6)
Location: include/net/ipv6.h:775
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd224f)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe144c)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/udp.c (ffffffff81fe9964)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffb3da)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff8200360e)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820249dd)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/mptcp/subflow.c (ffffffff8207c0a4)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_info2sockaddr
  - net/mptcp/subflow.c:subflow_v6_conn_request
```
```
In net/mptcp/pm.c (ffffffff82081f7b)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_addr_families_match
  - net/mptcp/pm.c:mptcp_pm_addr_families_match
```
```
In net/mptcp/pm_netlink.c (ffffffff82085889)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_addresses_equal
  - net/mptcp/pm_netlink.c:mptcp_addresses_equal
```
```
In lib/vsprintf.c (ffffffff820beb3d)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/core/sock.c (ffffffff81ec4d3b)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc2422)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc6ebe)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_match_addr_any
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc87f3)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcced7)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff44d9)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffc939)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/tcp_ao.c (ffffffff82055642)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_del_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
  - net/ipv4/tcp_ao.c:tcp_ao_prepare_reset
  - net/ipv4/tcp_ao.c:__tcp_ao_do_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff82083596)
Location: include/net/ipv6.h:775
Inline: True
```
```
In net/ipv6/route.c (ffffffff8209f7df)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820af1ad)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/udp.c (ffffffff820b79fa)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8cba)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff820d23e5)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3cce)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/mptcp/subflow.c (ffffffff82151574)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_info2sockaddr
  - net/mptcp/subflow.c:subflow_v6_conn_request
```
```
In net/mptcp/pm.c (ffffffff8215756b)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_addr_families_match
  - net/mptcp/pm.c:mptcp_pm_addr_families_match
```
```
In net/mptcp/pm_netlink.c (ffffffff8215a509)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_addresses_equal
  - net/mptcp/pm_netlink.c:mptcp_addresses_equal
```
```
In net/mptcp/pm_userspace.c (ffffffff821614b8)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
```
```
In lib/vsprintf.c (ffffffff8219942d)
Location: include/net/ipv6.h:775
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/ipv4/ip_sockglue.c (ffff800010c67a28)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6ac1c)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c89e9c)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffff800010c927e4)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffff800010cf9d50)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/ip6_input.c (ffff800010cfd354)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/route.c (ffff800010d133e8)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1ebcc)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d253b0)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d36e58)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffff800010d3d16c)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55aa4)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (ffff800010d94d80)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/ipv4/ip_sockglue.c (c0d768d4)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (c0d79cbc)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (c0d98fb0)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (c0da1204)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (c0dfe710)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/ip6_input.c (c0e04604)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (c0e18504)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (c0e23748)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/udp.c (c0e28ad4)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (c0e39c30)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c0e40438)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (c0e56078)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (c0e90ecc)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/ipv4/ip_sockglue.c (c000000000d6bbc8)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (c000000000d6ff0c)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9746c)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (c000000000da180c)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (c000000000e1ec38)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/ip6_input.c (c000000000e24e00)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (c000000000e3ed78)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4dcb0)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/udp.c (c000000000e54d34)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (c000000000e688b0)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c000000000e71358)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e990)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (c000000000ed9940)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/ipv4/ip_sockglue.c (ffffffe0007cdef6)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d094a)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eac46)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f162e)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffe0008432dc)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/ip6_input.c (ffffffe000847724)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (ffffffe000858b52)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe000861b40)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/udp.c (ffffffe000865e30)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008739ae)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffe0008799c2)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d262)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (ffffffe0008bea46)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/ipv4/ip_sockglue.c (ffffffff81956398)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff81959386)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81976d1a)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e1fa)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff819d695b)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/ip6_input.c (ffffffff819db437)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ee07e)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f9a03)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819ff246)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d1f7)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a13e41)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a28354)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (ffffffff81a5931f)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/ipv4/ip_sockglue.c (ffffffff8190fe88)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff81912e76)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819307da)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff81937cba)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff8199371b)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/ip6_input.c (ffffffff819981f7)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/route.c (ffffffff819aae3e)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b67c3)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bc006)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c9fb7)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819d0c01)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e5114)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (ffffffff81a163ff)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/ipv4/ip_sockglue.c (ffffffff819c0b68)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3b56)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e14ea)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e89ca)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81a413db)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/ip6_input.c (ffffffff81a45eb7)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a58afe)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a64483)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a69cc6)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a77c77)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a7e8c1)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a93f04)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (ffffffff81ac570f)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
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
In net/ipv4/ip_sockglue.c (ffffffff819ca548)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_send
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd5a6)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb21a)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f272a)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/ip6_output.c (ffffffff81a4cfa3)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/ip6_input.c (ffffffff81a51ba3)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a64cd9)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a70999)
Location: include/net/ipv6.h:687
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a762d6)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a843e7)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a8b172)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa0054)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (ffffffff81ad19df)
Location: include/net/ipv6.h:687
Inline: True
Inline callers:
  - lib/vsprintf.c:ip6_compressed_string
```
</details>
</li>
</ul>

## Differences
