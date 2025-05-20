# Function: <code>ipv6_portaddr_hash</code>

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
In net/ipv4/inet_hashtables.c (ffffffff818f1e8d)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (ffffffff8198537a)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
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
In net/ipv6/inet6_hashtables.c (ffffffff819ac822)
Location: include/net/ipv6.h:649
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff8191fb8d)
Location: include/net/ipv6.h:641
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (ffffffff819bbaf4)
Location: include/net/ipv6.h:641
Inline: True
Inline callers:
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
In net/ipv6/inet6_hashtables.c (ffffffff819e3366)
Location: include/net/ipv6.h:641
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff8198249c)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (ffffffff81a2a732)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
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
In net/ipv6/inet6_hashtables.c (ffffffff81a520b1)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff819b8d0f)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (ffffffff81a61285)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
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
In net/ipv6/inet6_hashtables.c (ffffffff81a88cb4)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa3816)
Location: include/net/ipv6.h:704
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b59cb0)
Location: include/net/ipv6.h:704
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_demux_lookup
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83d00)
Location: include/net/ipv6.h:704
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81b59cb0-ffffffff81b59dd6: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
ffffffff81b83d00-ffffffff81b83e26: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aade56)
Location: include/net/ipv6.h:704
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b68310)
Location: include/net/ipv6.h:704
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_demux_lookup
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93560)
Location: include/net/ipv6.h:704
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81b68310-ffffffff81b68436: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
ffffffff81b93560-ffffffff81b93686: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a98e1b)
Location: include/net/ipv6.h:705
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b56610)
Location: include/net/ipv6.h:705
Inline: True
Direct callers:
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
In net/ipv6/inet6_hashtables.c (ffffffff81b82680)
Location: include/net/ipv6.h:705
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81b56610-ffffffff81b5672d: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
ffffffff81b82680-ffffffff81b8279d: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b542e0)
Location: include/net/ipv6.h:708
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (ffffffff81c1c0d0)
Location: include/net/ipv6.h:708
Inline: True
Direct callers:
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
In net/ipv6/inet6_hashtables.c (ffffffff81c4e750)
Location: include/net/ipv6.h:708
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81c1c0d0-ffffffff81c1c1ed: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
ffffffff81c4e750-ffffffff81c4e86d: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce2455)
Location: include/net/ipv6.h:762
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (ffffffff81db88a0)
Location: include/net/ipv6.h:762
Inline: True
Direct callers:
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
In net/ipv6/inet6_hashtables.c (ffffffff81def050)
Location: include/net/ipv6.h:762
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81db88a0-ffffffff81db89e1: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
ffffffff81def050-ffffffff81def191: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea3390)
Location: include/net/ipv6.h:795
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bhash2_addr_any_hashbucket
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5d4f)
Location: include/net/ipv6.h:795
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81eaa300)
Location: include/net/ipv6.h:795
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv6/udp.c (ffffffff81f888e0)
Location: include/net/ipv6.h:795
Inline: True
Direct callers:
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
In net/ipv6/inet6_hashtables.c (ffffffff81fc30f0)
Location: include/net/ipv6.h:795
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81ea3390-ffffffff81ea34d1: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
ffffffff81f888e0-ffffffff81f88a21: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
ffffffff81fc30f0-ffffffff81fc3231: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f01bd0)
Location: include/net/ipv6.h:792
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bhash2_addr_any_hashbucket
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f044c0)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f08b21)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv6/udp.c (ffffffff81feb47f)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
Direct callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820249d0)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81f01bd0-ffffffff81f01d11: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
ffffffff81feab30-ffffffff81feac71: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc5c90)
Location: include/net/ipv6.h:792
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bhash2_addr_any_hashbucket
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc87e6)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fccec8)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv6/udp.c (ffffffff820b913f)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
Direct callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3cc1)
Location: include/net/ipv6.h:792
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81fc5c90-ffffffff81fc5dd1: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
ffffffff820b88b0-ffffffff820b89f1: ipv6_portaddr_hash.isra.0 (STB_LOCAL)
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
In net/ipv4/inet_hashtables.c (ffff800010c6a288)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (ffff800010d244e4)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
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
In net/ipv6/inet6_hashtables.c (ffff800010d559d0)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (c0d796ac)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (c0e2b340)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
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
In net/ipv6/inet6_hashtables.c (c0e55f88)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (c000000000d6f6a0)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (c000000000e56d64)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
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
In net/ipv6/inet6_hashtables.c (c000000000e8e978)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffe0007d002e)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (ffffffe000868004)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
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
In net/ipv6/inet6_hashtables.c (ffffffe00088d166)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff81958b7f)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (ffffffff81a00915)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
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
In net/ipv6/inet6_hashtables.c (ffffffff81a28344)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff8191266f)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (ffffffff819bd6d5)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
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
In net/ipv6/inet6_hashtables.c (ffffffff819e5104)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff819c334f)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (ffffffff81a6b395)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
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
In net/ipv6/inet6_hashtables.c (ffffffff81a93ef4)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff819cd01f)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/udp.c (ffffffff81a779a5)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
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
In net/ipv6/inet6_hashtables.c (ffffffff81aa0044)
Location: include/net/ipv6.h:699
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
</ul>

## Differences
