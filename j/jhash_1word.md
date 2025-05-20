# Function: <code>jhash_1word</code>

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
In kernel/workqueue.c (ffffffff8109b707)
Location: include/linux/jhash.h:170
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff817546d2)
Location: include/linux/jhash.h:170
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:find_exception
```
```
In net/ipv4/udp.c (ffffffff81788b15)
Location: include/linux/jhash.h:170
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/udp.c (ffffffff817e34ef)
Location: include/linux/jhash.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_portaddr_hash
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
In kernel/workqueue.c (ffffffff8109ed17)
Location: include/linux/jhash.h:170
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff817c1053)
Location: include/linux/jhash.h:170
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/udp.c (ffffffff817f8162)
Location: include/linux/jhash.h:170
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff81851bef)
Location: include/linux/jhash.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_portaddr_hash
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
In kernel/workqueue.c (ffffffff810a3be6)
Location: include/linux/jhash.h:170
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff817f0653)
Location: include/linux/jhash.h:170
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/udp.c (ffffffff81829002)
Location: include/linux/jhash.h:170
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff818839af)
Location: include/linux/jhash.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_portaddr_hash
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
In kernel/workqueue.c (ffffffff810a0d65)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff81810a9b)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/udp.c (ffffffff8184a226)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff818a9c22)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_portaddr_hash
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
In kernel/workqueue.c (ffffffff810a75b4)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff8188feff)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/udp.c (ffffffff818c9d97)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff8192c622)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_portaddr_hash
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
In kernel/workqueue.c (ffffffff810ae11b)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff818e2e4b)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2034)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (ffffffff8191fd69)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff819853a1)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ac833)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/workqueue.c (ffffffff810b724e)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff8190fceb)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f9ee)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (ffffffff8194e9d3)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff819bbb1b)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3376)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/workqueue.c (ffffffff810bc5de)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff819722eb)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff819822fa)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (ffffffff819b31bc)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff81a2a958)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a521e5)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/workqueue.c (ffffffff810c332e)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff819a8c5b)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b8b51)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (ffffffff819e9f3f)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff81a614ab)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a88de8)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/workqueue.c (ffffffff810cadb5)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff814bf4f5)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In net/ipv4/route.c (ffffffff81a9351b)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa3571)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81ad7b1d)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff81b59cbe)
Location: include/linux/jhash.h:169
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83d0e)
Location: include/linux/jhash.h:169
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
In kernel/workqueue.c (ffffffff810c5ee5)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff814dcf15)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In net/ipv4/route.c (ffffffff81a9d3cb)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aadab5)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81ae416d)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff81b6831e)
Location: include/linux/jhash.h:171
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b9356e)
Location: include/linux/jhash.h:171
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
In kernel/workqueue.c (ffffffff810c7825)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff814e3875)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98b76)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81acf367)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff81b5661c)
Location: include/linux/jhash.h:171
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b8268c)
Location: include/linux/jhash.h:171
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
In kernel/workqueue.c (ffffffff810da585)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff8153cc65)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54056)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (ffffffff81b8dd87)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff81c1c0dc)
Location: include/linux/jhash.h:171
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e75c)
Location: include/linux/jhash.h:171
Inline: True
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
In kernel/workqueue.c (ffffffff810f3cc6)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff815d4665)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1f67)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (ffffffff81d1efaf)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff81db88ac)
Location: include/linux/jhash.h:171
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def05c)
Location: include/linux/jhash.h:171
Inline: True
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
In kernel/workqueue.c (ffffffff81115f16)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff81682775)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea53cb)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bhash2_addr_any_hashbucket
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5b9c)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81eaa169)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/udp.c (ffffffff81ee60c7)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff81f888ec)
Location: include/linux/jhash.h:171
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc30fc)
Location: include/linux/jhash.h:171
Inline: True
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
In kernel/workqueue.c (ffffffff81122cb6)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff816ba8f5)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f03b53)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bhash2_addr_any_hashbucket
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f0431d)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f08983)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/udp.c (ffffffff81f458c7)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff81feb484)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820249f8)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/workqueue.c (ffffffff8112cc85)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:get_unbound_pool
```
```
In security/selinux/ss/ebitmap.c (ffffffff816f7385)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_hash
  - security/selinux/ss/ebitmap.c:ebitmap_hash
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7e06)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bhash2_addr_any_hashbucket
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc866d)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fccbe5)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/udp.c (ffffffff8200ba17)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff820b9144)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3ce9)
Location: include/linux/jhash.h:171
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/workqueue.c (ffff8000101210a4)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffff800010c59878)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffff800010c69f64)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (ffff800010c9f74c)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffff800010d244fc)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d559e0)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/workqueue.c (c0374fe4)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (c0d68170)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (c0d794b4)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (c0daca78)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (c0e2b370)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (c0e55fcc)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/workqueue.c (c00000000016a624)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (c000000000d5a168)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (c000000000d6f4f0)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (c000000000db21f8)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (c000000000e56d90)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8eb10)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/workqueue.c (ffffffe0000d9ff0)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffe0007c24e2)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cfdd2)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (ffffffe0007fc24a)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffe000868048)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d18a)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/workqueue.c (ffffffff810bd69e)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff81948acb)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff819589c1)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (ffffffff81989daf)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff81a00b3b)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a28478)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/workqueue.c (ffffffff810abece)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff819025bb)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff819124b1)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (ffffffff8194386f)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff819bd8fb)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e5238)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/workqueue.c (ffffffff810bcbfe)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff819b329b)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3191)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (ffffffff819f457f)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff81a6b5bb)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a94028)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In kernel/workqueue.c (ffffffff810c4f7e)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In net/ipv4/route.c (ffffffff819bc96b)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cce61)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/udp.c (ffffffff819fe73f)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_v4_rehash
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv4/udp.c:udp_v4_get_port
```
```
In net/ipv6/udp.c (ffffffff81a77bcb)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa0178)
Location: include/linux/jhash.h:169
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
</ul>

## Differences
