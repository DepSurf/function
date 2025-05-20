# Function: <code>inet_bound_dev_eq</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8191f68b)
Location: include/net/inet_sock.h:146
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffffffff81946e7a)
Location: include/net/inet_sock.h:146
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (ffffffff8194bd4d)
Location: include/net/inet_sock.h:146
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff819bcbc1)
Location: include/net/inet_sock.h:146
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff819bd5cb)
Location: include/net/inet_sock.h:146
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3278)
Location: include/net/inet_sock.h:146
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff81981fef)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffffffff819ab4fa)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (ffffffff819b346a)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81a2b70c)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81a2c06b)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a51fbc)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff819b884f)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffffffff819e21ca)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (ffffffff819ea1f0)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81a6226f)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81a62bcb)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a88bbc)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff81aa345f)
Location: include/net/inet_sock.h:142
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81acf85c)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (ffffffff81ad2ded)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_mcast_demux_lookup
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
```
```
In net/ipv6/udp.c (ffffffff81b59eff)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
```
In net/ipv6/raw.c (ffffffff81b5b48b)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b8453c)
Location: include/net/inet_sock.h:142
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
In net/ipv4/inet_hashtables.c (ffffffff81aad98d)
Location: include/net/inet_sock.h:142
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81adb87c)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (ffffffff81adf22d)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_mcast_demux_lookup
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
```
```
In net/ipv6/udp.c (ffffffff81b6855f)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
```
In net/ipv6/raw.c (ffffffff81b69cab)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93d89)
Location: include/net/inet_sock.h:142
Inline: True
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
In net/ipv4/inet_hashtables.c (ffffffff81a98a4e)
Location: include/net/inet_sock.h:142
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81ac68c6)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (ffffffff81acf633)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
```
```
In net/ipv6/udp.c (ffffffff81b56854)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
```
In net/ipv6/raw.c (ffffffff81b57f9c)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82e9a)
Location: include/net/inet_sock.h:142
Inline: True
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
In net/ipv4/inet_hashtables.c (ffffffff81b53f2d)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffffffff81b850d6)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (ffffffff81b8e05c)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81c1cd04)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81c1f54c)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4ef68)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff81ce2929)
Location: include/net/inet_sock.h:144
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffffffff81d178bf)
Location: include/net/inet_sock.h:144
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81d1f1e7)
Location: include/net/inet_sock.h:144
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81dbbca0)
Location: include/net/inet_sock.h:144
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81dbc145)
Location: include/net/inet_sock.h:144
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def791)
Location: include/net/inet_sock.h:144
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In net/ipv4/inet_hashtables.c (ffffffff81ea3dbb)
Location: include/net/inet_sock.h:144
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffffffff81ede17f)
Location: include/net/inet_sock.h:144
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ee62ff)
Location: include/net/inet_sock.h:144
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81f8bdc8)
Location: include/net/inet_sock.h:144
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81f8c365)
Location: include/net/inet_sock.h:144
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3861)
Location: include/net/inet_sock.h:144
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In net/ipv4/inet_hashtables.c (ffffffff81f02606)
Location: include/net/inet_sock.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffffffff81f3d498)
Location: include/net/inet_sock.h:145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81f45af7)
Location: include/net/inet_sock.h:145
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:compute_score
```
```
In net/ipv6/udp.c (ffffffff81fec568)
Location: include/net/inet_sock.h:145
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:compute_score
```
```
In net/ipv6/raw.c (ffffffff81fecb35)
Location: include/net/inet_sock.h:145
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820246ac)
Location: include/net/inet_sock.h:145
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In net/ipv4/inet_hashtables.c (ffffffff81fc69c6)
Location: include/net/inet_sock.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffffffff820035f8)
Location: include/net/inet_sock.h:145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff8200bc47)
Location: include/net/inet_sock.h:145
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:compute_score
```
```
In net/ipv6/udp.c (ffffffff820ba178)
Location: include/net/inet_sock.h:145
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:compute_score
```
```
In net/ipv6/raw.c (ffffffff820ba735)
Location: include/net/inet_sock.h:145
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f39bc)
Location: include/net/inet_sock.h:145
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In net/ipv4/inet_hashtables.c (ffff800010c69cbc)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffff800010c961d4)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (ffff800010c9f9cc)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffff800010d2728c)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffff800010d27e20)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d5589c)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (c0d78f74)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (c0da499c)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (c0dacd28)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (c0e2ad78)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (c0e2c894)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (c0e55ea0)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (c000000000d6ece8)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (c000000000da7714)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (c000000000db25ec)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (c000000000e581bc)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (c000000000e58e7c)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e7fc)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffe0007cfad0)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffffffe0007f52a4)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (ffffffe0007fc4c8)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffe000867948)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffe000869690)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d08e)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff819586bf)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffffffff8198203a)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (ffffffff8198a060)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81a018ff)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81a0225b)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a2824c)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff819121af)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffffffff8193bafa)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (ffffffff81943b20)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff819be6bf)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff819bf01b)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e500c)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff819c2e8f)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffffffff819ec80a)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (ffffffff819f4830)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81a6c37f)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81a6ccdb)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a93dfc)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
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
In net/ipv4/inet_hashtables.c (ffffffff819cc95f)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/raw.c (ffffffff819f66fa)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:__raw_v4_lookup
```
```
In net/ipv4/udp.c (ffffffff819fe9f0)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81a7898f)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81a7931b)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9ff4c)
Location: include/net/inet_sock.h:142
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
</ul>

## Differences
