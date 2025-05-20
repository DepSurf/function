# Function: <code>__skb_decr_checksum_unnecessary</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177e50a)
Location: include/linux/skbuff.h:3094
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8178a2dd)
Location: include/linux/skbuff.h:3094
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8178f243)
Location: include/linux/skbuff.h:3094
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8179766d)
Location: include/linux/skbuff.h:3094
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff817e8776)
Location: include/linux/skbuff.h:3094
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f1c38)
Location: include/linux/skbuff.h:3094
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81800358)
Location: include/linux/skbuff.h:3094
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81802655)
Location: include/linux/skbuff.h:3094
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
In net/ipv4/tcp_ipv4.c (ffffffff817ebabf)
Location: include/linux/skbuff.h:3301
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff817f7631)
Location: include/linux/skbuff.h:3301
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff817fc8ab)
Location: include/linux/skbuff.h:3301
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81805f74)
Location: include/linux/skbuff.h:3301
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81856f2e)
Location: include/linux/skbuff.h:3301
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818605fa)
Location: include/linux/skbuff.h:3301
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81871911)
Location: include/linux/skbuff.h:3301
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81873958)
Location: include/linux/skbuff.h:3301
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff8181c435)
Location: include/linux/skbuff.h:3353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81828544)
Location: include/linux/skbuff.h:3353
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8182d80e)
Location: include/linux/skbuff.h:3353
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81836ff4)
Location: include/linux/skbuff.h:3353
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888d2e)
Location: include/linux/skbuff.h:3353
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818925a4)
Location: include/linux/skbuff.h:3353
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5e71)
Location: include/linux/skbuff.h:3353
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a7fd8)
Location: include/linux/skbuff.h:3353
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff8183ca75)
Location: include/linux/skbuff.h:3421
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81849849)
Location: include/linux/skbuff.h:3421
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8184ec22)
Location: include/linux/skbuff.h:3421
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8185856b)
Location: include/linux/skbuff.h:3421
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af3b0)
Location: include/linux/skbuff.h:3421
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8a9e)
Location: include/linux/skbuff.h:3421
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc8d3)
Location: include/linux/skbuff.h:3421
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce824)
Location: include/linux/skbuff.h:3421
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff818bc1d7)
Location: include/linux/skbuff.h:3605
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff818c9397)
Location: include/linux/skbuff.h:3605
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff818ce9a2)
Location: include/linux/skbuff.h:3605
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff818d843b)
Location: include/linux/skbuff.h:3605
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff819320c0)
Location: include/linux/skbuff.h:3605
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b95c)
Location: include/linux/skbuff.h:3605
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81951683)
Location: include/linux/skbuff.h:3605
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff819536d4)
Location: include/linux/skbuff.h:3605
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff81911b75)
Location: include/linux/skbuff.h:3615
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8191f592)
Location: include/linux/skbuff.h:3615
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff81924ec4)
Location: include/linux/skbuff.h:3615
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8192ed5a)
Location: include/linux/skbuff.h:3615
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198ac25)
Location: include/linux/skbuff.h:3615
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994b81)
Location: include/linux/skbuff.h:3615
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aad30)
Location: include/linux/skbuff.h:3615
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad0fa)
Location: include/linux/skbuff.h:3615
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff81940346)
Location: include/linux/skbuff.h:3700
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8194e226)
Location: include/linux/skbuff.h:3700
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff81953cca)
Location: include/linux/skbuff.h:3700
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8195e1b1)
Location: include/linux/skbuff.h:3700
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c14f2)
Location: include/linux/skbuff.h:3700
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb46f)
Location: include/linux/skbuff.h:3700
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e185c)
Location: include/linux/skbuff.h:3700
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3aa7)
Location: include/linux/skbuff.h:3700
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff819a488b)
Location: include/linux/skbuff.h:3809
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819b2a9b)
Location: include/linux/skbuff.h:3809
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff819b85d1)
Location: include/linux/skbuff.h:3809
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff819c354f)
Location: include/linux/skbuff.h:3809
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a302d9)
Location: include/linux/skbuff.h:3809
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39ed4)
Location: include/linux/skbuff.h:3809
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a5061b)
Location: include/linux/skbuff.h:3809
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a52813)
Location: include/linux/skbuff.h:3809
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
In net/ipv4/tcp_ipv4.c (ffffffff819db58b)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819e983b)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff819ef2d1)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff819fa0ef)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a66e29)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70a64)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a8723b)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a893f3)
Location: include/linux/skbuff.h:3876
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
In net/core/filter.c (ffffffff81a230e9)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac862f)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ad3399)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81add223)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ae89c7)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5f8b6)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a23b)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b82517)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b848cf)
Location: include/linux/skbuff.h:3902
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
In net/core/filter.c (ffffffff81a23449)
Location: include/linux/skbuff.h:3931
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad45cf)
Location: include/linux/skbuff.h:3931
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81adf792)
Location: include/linux/skbuff.h:3931
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81ae9f73)
Location: include/linux/skbuff.h:3931
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81af58c7)
Location: include/linux/skbuff.h:3931
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6e056)
Location: include/linux/skbuff.h:3931
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78d17)
Location: include/linux/skbuff.h:3931
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91c07)
Location: include/linux/skbuff.h:3931
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b9422f)
Location: include/linux/skbuff.h:3931
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
In net/core/filter.c (ffffffff81a0a771)
Location: include/linux/skbuff.h:3995
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf708)
Location: include/linux/skbuff.h:3995
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81aca698)
Location: include/linux/skbuff.h:3995
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81ad5773)
Location: include/linux/skbuff.h:3995
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ae1023)
Location: include/linux/skbuff.h:3995
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c45a)
Location: include/linux/skbuff.h:3995
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67829)
Location: include/linux/skbuff.h:3995
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80e56)
Location: include/linux/skbuff.h:3995
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b8333d)
Location: include/linux/skbuff.h:3995
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
In net/core/filter.c (ffffffff81abcc51)
Location: include/linux/skbuff.h:4032
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d260)
Location: include/linux/skbuff.h:4032
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81b88f78)
Location: include/linux/skbuff.h:4032
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81b94521)
Location: include/linux/skbuff.h:4032
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ba06c3)
Location: include/linux/skbuff.h:4032
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c23cf6)
Location: include/linux/skbuff.h:4032
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f50c)
Location: include/linux/skbuff.h:4032
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4ce76)
Location: include/linux/skbuff.h:4032
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f40d)
Location: include/linux/skbuff.h:4032
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
In net/core/filter.c (ffffffff81c3772d)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d143)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81d1a9b3)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81d25daf)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81d32b9a)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc0c28)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc8a1)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded2b5)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defde7)
Location: include/linux/skbuff.h:4451
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
In net/core/filter.c (ffffffff81deaf8d)
Location: include/linux/skbuff.h:4347
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2bc1)
Location: include/linux/skbuff.h:4347
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ee16e3)
Location: include/linux/skbuff.h:4347
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81eed627)
Location: include/linux/skbuff.h:4347
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81efae2a)
Location: include/linux/skbuff.h:4347
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81f911ee)
Location: include/linux/skbuff.h:4347
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d9e0)
Location: include/linux/skbuff.h:4347
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc10c5)
Location: include/linux/skbuff.h:4347
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3ef7)
Location: include/linux/skbuff.h:4347
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
In net/core/filter.c (ffffffff81e5c78d)
Location: include/linux/skbuff.h:4379
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f318a8)
Location: include/linux/skbuff.h:4379
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81f41126)
Location: include/linux/skbuff.h:4379
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81f4cfea)
Location: include/linux/skbuff.h:4379
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81f5a8bb)
Location: include/linux/skbuff.h:4379
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81ff1ad7)
Location: include/linux/skbuff.h:4379
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe460)
Location: include/linux/skbuff.h:4379
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff82022058)
Location: include/linux/skbuff.h:4379
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024f17)
Location: include/linux/skbuff.h:4379
Inline: True
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
In net/core/filter.c (ffffffff81f1bb7d)
Location: include/linux/skbuff.h:4419
Inline: True
Inline callers:
  - net/core/filter.c:bpf_csum_level
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7a9f)
Location: include/linux/skbuff.h:4419
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff82006d76)
Location: include/linux/skbuff.h:4419
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff820130fa)
Location: include/linux/skbuff.h:4419
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff82020dfb)
Location: include/linux/skbuff.h:4419
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff820bf6d6)
Location: include/linux/skbuff.h:4419
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd342)
Location: include/linux/skbuff.h:4419
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f1178)
Location: include/linux/skbuff.h:4419
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f41f7)
Location: include/linux/skbuff.h:4419
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffff800010c8e948)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffff800010c9ef0c)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffff800010ca50f8)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffff800010cb17ec)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2ce34)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38f2c)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffff800010d53980)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffff800010d5623c)
Location: include/linux/skbuff.h:3876
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
In net/ipv4/tcp_ipv4.c (c0d9d8a8)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (c0dac314)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (c0db1a14)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (c0dbd3cc)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (c0e30de4)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3bae4)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (c0e54280)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (c0e56838)
Location: include/linux/skbuff.h:3876
Inline: True
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
In net/ipv4/tcp_ipv4.c (c000000000d9d4b0)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (c000000000db17f4)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (c000000000db8d50)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (c000000000dc8684)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (c000000000e5e890)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c550)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (c000000000e8c0b8)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f3a4)
Location: include/linux/skbuff.h:3876
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffe0007eed28)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffe0007fb990)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffe00080096a)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffe00080a228)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086cfd8)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008763d8)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b57a)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088dabc)
Location: include/linux/skbuff.h:3876
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff8197b3fb)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819896ab)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8198f071)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81999e8f)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a064b9)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a100f4)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a268cb)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28a83)
Location: include/linux/skbuff.h:3876
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
In net/ipv4/tcp_ipv4.c (ffffffff81934ebb)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8194316b)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff81948b31)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8195394f)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c3279)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cceb4)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e368b)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5c73)
Location: include/linux/skbuff.h:3876
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
In net/ipv4/tcp_ipv4.c (ffffffff819e5bcb)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819f3e7b)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff819f9911)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81a0472f)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a70f39)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7ab74)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9247b)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a94633)
Location: include/linux/skbuff.h:3876
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
In net/ipv4/tcp_ipv4.c (ffffffff819ef88b)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819fe03b)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff81a03c01)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81a0ecaf)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d549)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a873b4)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e52b)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0793)
Location: include/linux/skbuff.h:3876
Inline: True
```
</details>
</li>
</ul>

## Differences
