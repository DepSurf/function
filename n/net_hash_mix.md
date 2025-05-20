# Function: <code>net_hash_mix</code>

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
In net/ipv4/route.c (0)
Location: include/net/netns/hash.h:8
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762f97)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/netns/hash.h:8
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81763bdb)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netns/hash.h:8
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8178901d)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netns/hash.h:8
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:8
Inline: True
```
```
In net/ipv6/udp.c (ffffffff817e34c9)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/output_core.c (0)
Location: include/net/netns/hash.h:8
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/netns/hash.h:8
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
In net/ipv4/route.c (ffffffff817c0f51)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cf3d4)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cf807)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d00d2)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee4ae)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (ffffffff817f7fa5)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff817fe5d0)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/ping.c (ffffffff81811736)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/udp.c (ffffffff81852d36)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/output_core.c (ffffffff81871eac)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8187332b)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/route.c (ffffffff817f0551)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ff1c4)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff5f7)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817ffeff)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181eeae)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (ffffffff81828e45)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff8182f530)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/ping.c (ffffffff81842c46)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/udp.c (ffffffff81884a3a)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/output_core.c (ffffffff818a648c)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7958)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/route.c (ffffffff8180ed81)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181e718)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181f827)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81821003)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183faed)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (ffffffff8184a12b)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv4/devinet.c (ffffffff81850a1c)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/ping.c (ffffffff818644c6)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/udp.c (ffffffff818aad5d)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/output_core.c (ffffffff818ccedc)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce225)
Location: include/net/netns/hash.h:8
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/route.c (ffffffff8188e329)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189d638)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189e797)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fdc3)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bee8d)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (ffffffff818c9d0c)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv4/devinet.c (ffffffff818d0653)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/ping.c (ffffffff818e4606)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/addrconf.c (ffffffff81916aa9)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/udp.c (ffffffff8192d8d0)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/output_core.c (ffffffff81951ccc)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81953085)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/route.c (ffffffff818e203f)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f23e3)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f33a7)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4921)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914a6a)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (ffffffff8191fd69)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv4/devinet.c (ffffffff81926be4)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/ping.c (ffffffff8193aed3)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/addrconf.c (ffffffff8196e16a)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/udp.c (ffffffff8198537a)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/output_core.c (ffffffff819ab28c)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ac7d4)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/route.c (ffffffff8190eedf)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191fde3)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920ec7)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819226ca)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194321a)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (ffffffff8194e9d3)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv4/devinet.c (ffffffff81955c94)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/ping.c (ffffffff8196abc3)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197bf45)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/anycast.c (ffffffff8199400c)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff819a3cea)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/udp.c (ffffffff819bbaf4)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/output_core.c (ffffffff819e1dac)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3366)
Location: include/net/netns/hash.h:9
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/inet_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
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
In net/ipv4/inet_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
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
In net/ipv4/inet_hashtables.c (ffffffff81aa44af)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4b17)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa73f4)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb940)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics_req
```
```
In net/ipv4/udp.c (ffffffff81ad2d37)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_mcast_demux_lookup
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81ae0095)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f685)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff81b2c0ed)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/addrconf.c (ffffffff81b3dc53)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
```
```
In net/ipv6/udp.c (ffffffff81b59e36)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83ec8)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/inet_hashtables.c (ffffffff81aaeaff)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf177)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab1a84)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7901)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics_req
```
```
In net/ipv4/udp.c (ffffffff81adf177)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_mcast_demux_lookup
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81aecf15)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1d975)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff81b3ab12)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/addrconf.c (ffffffff81b4c7d3)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
```
```
In net/ipv6/udp.c (ffffffff81b68496)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93728)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff81bc9501)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
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
In net/ipv4/inet_hashtables.c (ffffffff81a99d3f)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a48a)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ccf3)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2a99)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (ffffffff81acf529)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81ad86f5)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0b1c5)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff81b287f2)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/addrconf.c (ffffffff81b3a4a6)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/udp.c (ffffffff81b5678a)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b8283f)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff81bbccbc)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In net/ipv4/inet_hashtables.c (ffffffff81b551af)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b558fa)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b58a33)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b8145b)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (ffffffff81b8df52)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81b97585)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8c1d)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:ip_fib_check_default
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bce095)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff81bee7b5)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/addrconf.c (ffffffff81c00c46)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/udp.c (ffffffff81c1cc3a)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e90f)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff81c8cb1c)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In net/ipv4/inet_hashtables.c (ffffffff81ce2d6d)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce32fa)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce6c56)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d118ab)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (ffffffff81d1ef0d)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81d28c30)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3b67d)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:ip_fib_check_default
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d64165)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff81d86d33)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/addrconf.c (ffffffff81d9a8cf)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/udp.c (ffffffff81db9506)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def23f)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff81e361cc)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In net/ipv4/inet_hashtables.c (ffffffff81ea52cb)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5b78)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea9f1f)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed766b)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (ffffffff81ee6024)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81ef0690)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81f0404d)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:ip_fib_check_default
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2eee5)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff81f548f3)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/addrconf.c (ffffffff81f6971f)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/udp.c (ffffffff81f89576)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc32ef)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff8200f19c)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In net/ipv4/inet_hashtables.c (ffffffff81f03a5a)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f042f9)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f0878d)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f36a5b)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81f3d416)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81f45824)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff81f500f0)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63a2d)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:ip_fib_check_default
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8f425)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff81fb4303)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/addrconf.c (ffffffff81fc978f)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/udp.c (ffffffff81feafe6)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/raw.c (ffffffff81fef0a2)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024146)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff8208bd8c)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In net/ipv4/inet_hashtables.c (ffffffff81fc7d01)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8649)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fccaed)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffcb7b)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff82003576)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff8200b974)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_ehashfn
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffff820162a0)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff82029ffd)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_mtu
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:ip_fib_check_default
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d015)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff82081bb3)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/addrconf.c (ffffffff82096f2f)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/udp.c (ffffffff820b8a66)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_ehashfn
```
```
In net/ipv6/raw.c (ffffffff820bcc71)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f32b6)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
```
```
In net/mptcp/syncookies.c (ffffffff8216224c)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In net/ipv4/inet_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
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
In net/ipv4/inet_hashtables.c (c0d7a3f4)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a7d8)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c0d7d0dc)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (c0da06d4)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (c0daca78)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (c0db3ba8)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/ping.c (c0dcb738)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/xfrm/xfrm_policy.c (c0de226c)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/anycast.c (c0dfe128)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (c0e0ff98)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/udp.c (c0e2b340)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (c0e55f88)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/inet_hashtables.c (c000000000d70834)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70d84)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c000000000d74130)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (c000000000da1e80)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (c000000000db21f8)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (c000000000dbbc90)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/ping.c (c000000000ddc9a4)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/xfrm/xfrm_policy.c (c000000000df8df8)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/anycast.c (c000000000e1e5d4)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (c000000000e34198)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/udp.c (c000000000e56d64)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e978)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/inet_hashtables.c (ffffffe0007d0fba)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_ehashfn
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d1470)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2b84)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1a9e)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/udp.c (ffffffe0007fc2e6)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/devinet.c (ffffffe0008025d6)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_lookup_ifaddr_rcu
```
```
In net/ipv4/ping.c (ffffffe000815a12)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082b2de)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_key
```
```
In net/ipv6/anycast.c (ffffffe000842e42)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffe000851570)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/udp.c (ffffffe000868004)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d17a)
Location: include/net/netns/hash.h:7
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_ehashfn
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
In net/ipv4/inet_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
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
In net/ipv4/inet_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
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
In net/netfilter/nf_conntrack_core.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/netfilter/nf_conntrack_expect.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
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
In net/ipv4/inet_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/netns/hash.h:7
Inline: True
```
</details>
</li>
</ul>

## Differences
