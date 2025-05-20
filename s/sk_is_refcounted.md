# Function: <code>sk_is_refcounted</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4d39)
Location: include/net/sock.h:2555
Inline: True
Inline callers:
  - net/core/sock.c:sock_pfree
```
```
In net/core/filter.c (ffffffff81a2ba0d)
Location: include/net/sock.h:2555
Inline: True
Inline callers:
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_release
```
```
In net/core/sock_map.c (ffffffff81a4efbd)
Location: include/net/sock.h:2555
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8b4d)
Location: include/net/sock.h:2555
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ad7833)
Location: include/net/sock.h:2555
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff81b5af76)
Location: include/net/sock.h:2555
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a794)
Location: include/net/sock.h:2555
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/sock.c (ffffffff819e4489)
Location: include/net/sock.h:2576
Inline: True
Inline callers:
  - net/core/sock.c:sock_pfree
```
```
In net/core/filter.c (ffffffff81a304bb)
Location: include/net/sock.h:2576
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_release
```
```
In net/core/sock_map.c (ffffffff81a54b8c)
Location: include/net/sock.h:2576
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4aed)
Location: include/net/sock.h:2576
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ae3e83)
Location: include/net/sock.h:2576
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff81b6973c)
Location: include/net/sock.h:2576
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b791e3)
Location: include/net/sock.h:2576
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/sock.c (ffffffff819ca699)
Location: include/net/sock.h:2612
Inline: True
Inline callers:
  - net/core/sock.c:sock_pfree
```
```
In net/core/filter.c (ffffffff81a17424)
Location: include/net/sock.h:2612
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_release
```
```
In net/core/sock_map.c (ffffffff81a5104c)
Location: include/net/sock.h:2612
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfb9a)
Location: include/net/sock.h:2612
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81acf070)
Location: include/net/sock.h:2612
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff81b57a3a)
Location: include/net/sock.h:2612
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67d1d)
Location: include/net/sock.h:2612
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/sock.c (ffffffff81a79e87)
Location: include/net/sock.h:2671
Inline: True
Inline callers:
  - net/core/sock.c:sock_pfree
```
```
In net/core/filter.c (ffffffff81acdec2)
Location: include/net/sock.h:2671
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_release
```
```
In net/core/sock_map.c (ffffffff81b09390)
Location: include/net/sock.h:2671
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f301)
Location: include/net/sock.h:2671
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d714)
Location: include/net/sock.h:2671
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81b8db54)
Location: include/net/sock.h:2671
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff81c1f022)
Location: include/net/sock.h:2671
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f96c)
Location: include/net/sock.h:2671
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/sock.c (ffffffff81bedb87)
Location: include/net/sock.h:2781
Inline: True
```
```
In net/core/filter.c (ffffffff81c4bc37)
Location: include/net/sock.h:2781
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_release
```
```
In net/core/sock_map.c (ffffffff81c8f45f)
Location: include/net/sock.h:2781
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff81ccba65)
Location: include/net/sock.h:2781
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d6b8)
Location: include/net/sock.h:2781
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81d1ecfc)
Location: include/net/sock.h:2781
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff81dbb8a5)
Location: include/net/sock.h:2781
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccde3)
Location: include/net/sock.h:2781
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/sock.c (ffffffff81d9ae07)
Location: include/net/sock.h:2827
Inline: True
```
```
In net/core/filter.c (ffffffff81dfbc67)
Location: include/net/sock.h:2827
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_release
```
```
In net/core/sock_map.c (ffffffff81e4a6ff)
Location: include/net/sock.h:2827
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b8b5)
Location: include/net/sock.h:2827
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed3073)
Location: include/net/sock.h:2827
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ee5ce8)
Location: include/net/sock.h:2827
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff81f8b9e4)
Location: include/net/sock.h:2827
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9def0)
Location: include/net/sock.h:2827
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/sock.c (ffffffff81e09681)
Location: include/net/sock.h:2815
Inline: True
```
```
In net/core/filter.c (ffffffff81e6cb4d)
Location: include/net/sock.h:2815
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_release
```
```
In net/core/sock_map.c (ffffffff81ea5e0b)
Location: include/net/sock.h:2815
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff81ee98ff)
Location: include/net/sock.h:2815
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31dcb)
Location: include/net/sock.h:2815
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81f455cb)
Location: include/net/sock.h:2815
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff81fec0e7)
Location: include/net/sock.h:2815
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe99d)
Location: include/net/sock.h:2815
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/sock.c (ffffffff81ec6071)
Location: include/net/sock.h:2827
Inline: True
```
```
In net/core/filter.c (ffffffff81f2b57d)
Location: include/net/sock.h:2827
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_sk_release
```
```
In net/core/sock_map.c (ffffffff81f688cb)
Location: include/net/sock.h:2827
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
```
```
In net/netfilter/nf_queue.c (ffffffff81fad69e)
Location: include/net/sock.h:2827
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff4e21)
Location: include/net/sock.h:2827
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__inet_lookup_skb
```
```
In net/ipv4/udp.c (ffffffff8200b635)
Location: include/net/sock.h:2827
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff820b75f4)
Location: include/net/sock.h:2827
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c930d)
Location: include/net/sock.h:2827
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:__inet6_lookup_skb
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
