# Function: <code>__skb_checksum_validate_complete</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177e487)
Location: include/linux/skbuff.h:3174
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8178a1f9)
Location: include/linux/skbuff.h:3174
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8178f10f)
Location: include/linux/skbuff.h:3174
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8179762d)
Location: include/linux/skbuff.h:3174
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff817e867f)
Location: include/linux/skbuff.h:3174
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f1ba0)
Location: include/linux/skbuff.h:3174
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818002fa)
Location: include/linux/skbuff.h:3174
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff8180260a)
Location: include/linux/skbuff.h:3174
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
In net/ipv4/tcp_ipv4.c (ffffffff817eb899)
Location: include/linux/skbuff.h:3381
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff817f7598)
Location: include/linux/skbuff.h:3381
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff817fc76f)
Location: include/linux/skbuff.h:3381
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81805eea)
Location: include/linux/skbuff.h:3381
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81856e26)
Location: include/linux/skbuff.h:3381
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860405)
Location: include/linux/skbuff.h:3381
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818718db)
Location: include/linux/skbuff.h:3381
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81873902)
Location: include/linux/skbuff.h:3381
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
In net/ipv4/tcp_ipv4.c (ffffffff8181c209)
Location: include/linux/skbuff.h:3433
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff818284ab)
Location: include/linux/skbuff.h:3433
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8182d6cf)
Location: include/linux/skbuff.h:3433
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81836f6a)
Location: include/linux/skbuff.h:3433
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888c26)
Location: include/linux/skbuff.h:3433
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892395)
Location: include/linux/skbuff.h:3433
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5e3b)
Location: include/linux/skbuff.h:3433
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a7f82)
Location: include/linux/skbuff.h:3433
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
In net/ipv4/tcp_ipv4.c (ffffffff8183c9d6)
Location: include/linux/skbuff.h:3486
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff818496b7)
Location: include/linux/skbuff.h:3486
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8184eb6e)
Location: include/linux/skbuff.h:3486
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81858430)
Location: include/linux/skbuff.h:3486
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af2b8)
Location: include/linux/skbuff.h:3486
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b89f4)
Location: include/linux/skbuff.h:3486
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc947)
Location: include/linux/skbuff.h:3486
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce7de)
Location: include/linux/skbuff.h:3486
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
In net/ipv4/tcp_ipv4.c (ffffffff818bc12e)
Location: include/linux/skbuff.h:3670
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff818c90d9)
Location: include/linux/skbuff.h:3670
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff818ce8ee)
Location: include/linux/skbuff.h:3670
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff818d8300)
Location: include/linux/skbuff.h:3670
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81931fc8)
Location: include/linux/skbuff.h:3670
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b8a6)
Location: include/linux/skbuff.h:3670
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819516fe)
Location: include/linux/skbuff.h:3670
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff8195368e)
Location: include/linux/skbuff.h:3670
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
In net/ipv4/tcp_ipv4.c (ffffffff81911b44)
Location: include/linux/skbuff.h:3680
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8191f206)
Location: include/linux/skbuff.h:3680
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff81924cfe)
Location: include/linux/skbuff.h:3680
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8192ecde)
Location: include/linux/skbuff.h:3680
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198aaa7)
Location: include/linux/skbuff.h:3680
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994b45)
Location: include/linux/skbuff.h:3680
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aac25)
Location: include/linux/skbuff.h:3680
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad0b1)
Location: include/linux/skbuff.h:3680
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
In net/ipv4/tcp_ipv4.c (ffffffff81940315)
Location: include/linux/skbuff.h:3765
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8194de5f)
Location: include/linux/skbuff.h:3765
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff81953b0d)
Location: include/linux/skbuff.h:3765
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8195e135)
Location: include/linux/skbuff.h:3765
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c1369)
Location: include/linux/skbuff.h:3765
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb436)
Location: include/linux/skbuff.h:3765
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e1716)
Location: include/linux/skbuff.h:3765
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3a5e)
Location: include/linux/skbuff.h:3765
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
In net/ipv4/tcp_ipv4.c (ffffffff819a484c)
Location: include/linux/skbuff.h:3874
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819b264a)
Location: include/linux/skbuff.h:3874
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff819b83f0)
Location: include/linux/skbuff.h:3874
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff819c34cc)
Location: include/linux/skbuff.h:3874
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a3013f)
Location: include/linux/skbuff.h:3874
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39e92)
Location: include/linux/skbuff.h:3874
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a504d4)
Location: include/linux/skbuff.h:3874
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a527ca)
Location: include/linux/skbuff.h:3874
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
In net/ipv4/tcp_ipv4.c (ffffffff819db54c)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819e93ea)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff819ef0f0)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff819fa06c)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a66c8f)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70a22)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a870f4)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a893aa)
Location: include/linux/skbuff.h:3941
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
In net/ipv4/tcp_ipv4.c (ffffffff81ac85f1)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ad322e)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81add040)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ae8902)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5f6bf)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a1a0)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b823a7)
Location: include/linux/skbuff.h:3975
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b8483a)
Location: include/linux/skbuff.h:3975
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
In net/ipv4/tcp_ipv4.c (ffffffff81ad4591)
Location: include/linux/skbuff.h:4004
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81adf62f)
Location: include/linux/skbuff.h:4004
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81ae9d90)
Location: include/linux/skbuff.h:4004
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81af5802)
Location: include/linux/skbuff.h:4004
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6de5f)
Location: include/linux/skbuff.h:4004
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78c81)
Location: include/linux/skbuff.h:4004
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91a9b)
Location: include/linux/skbuff.h:4004
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b9419a)
Location: include/linux/skbuff.h:4004
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
In net/ipv4/tcp_ipv4.c (ffffffff81abf657)
Location: include/linux/skbuff.h:4068
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81aca531)
Location: include/linux/skbuff.h:4068
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81ad54ea)
Location: include/linux/skbuff.h:4068
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ae0f62)
Location: include/linux/skbuff.h:4068
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c1e2)
Location: include/linux/skbuff.h:4068
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b677d3)
Location: include/linux/skbuff.h:4068
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80cec)
Location: include/linux/skbuff.h:4068
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b832aa)
Location: include/linux/skbuff.h:4068
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
In net/ipv4/tcp_ipv4.c (ffffffff81b7d19f)
Location: include/linux/skbuff.h:4105
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81b88e11)
Location: include/linux/skbuff.h:4105
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81b942f0)
Location: include/linux/skbuff.h:4105
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ba0602)
Location: include/linux/skbuff.h:4105
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c23949)
Location: include/linux/skbuff.h:4105
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f403)
Location: include/linux/skbuff.h:4105
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4cd0c)
Location: include/linux/skbuff.h:4105
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f37a)
Location: include/linux/skbuff.h:4105
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
In net/ipv4/tcp_ipv4.c (ffffffff81d0d10f)
Location: include/linux/skbuff.h:4524
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81d1a884)
Location: include/linux/skbuff.h:4524
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81d25bbf)
Location: include/linux/skbuff.h:4524
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81d32ad7)
Location: include/linux/skbuff.h:4524
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc086f)
Location: include/linux/skbuff.h:4524
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc857)
Location: include/linux/skbuff.h:4524
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded17f)
Location: include/linux/skbuff.h:4524
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defd8e)
Location: include/linux/skbuff.h:4524
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
In net/ipv4/tcp_ipv4.c (ffffffff81ed2b87)
Location: include/linux/skbuff.h:4420
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ee15b4)
Location: include/linux/skbuff.h:4420
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81eed521)
Location: include/linux/skbuff.h:4420
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81efad67)
Location: include/linux/skbuff.h:4420
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81f90ff5)
Location: include/linux/skbuff.h:4420
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d996)
Location: include/linux/skbuff.h:4420
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc0f8f)
Location: include/linux/skbuff.h:4420
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3e9e)
Location: include/linux/skbuff.h:4420
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
In net/ipv4/tcp_ipv4.c (ffffffff81f3186e)
Location: include/linux/skbuff.h:4452
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81f40ff4)
Location: include/linux/skbuff.h:4452
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81f4cee1)
Location: include/linux/skbuff.h:4452
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81f5a807)
Location: include/linux/skbuff.h:4452
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81ff18e5)
Location: include/linux/skbuff.h:4452
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe416)
Location: include/linux/skbuff.h:4452
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff82021f1f)
Location: include/linux/skbuff.h:4452
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024ebe)
Location: include/linux/skbuff.h:4452
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
In net/ipv4/tcp_ipv4.c (ffffffff81ff7a6b)
Location: include/linux/skbuff.h:4492
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff82006c44)
Location: include/linux/skbuff.h:4492
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff82012ff1)
Location: include/linux/skbuff.h:4492
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff82020d47)
Location: include/linux/skbuff.h:4492
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff820bf4e4)
Location: include/linux/skbuff.h:4492
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd2f8)
Location: include/linux/skbuff.h:4492
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f103f)
Location: include/linux/skbuff.h:4492
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f419e)
Location: include/linux/skbuff.h:4492
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
In net/ipv4/tcp_ipv4.c (ffff800010c8e918)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffff800010c9ecc4)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffff800010ca4ee4)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffff800010cb1798)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2cbd4)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38ef4)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffff800010d53850)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffff800010d561c0)
Location: include/linux/skbuff.h:3941
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
In net/ipv4/tcp_ipv4.c (c0d9d874)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (c0dabf34)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (c0db17ec)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (c0dbd368)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (c0e30ac0)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3baa8)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (c0e54144)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (c0e567cc)
Location: include/linux/skbuff.h:3941
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
In net/ipv4/tcp_ipv4.c (c000000000d9d358)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (c000000000db1528)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (c000000000db8bec)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (c000000000dc860c)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (c000000000e5e6a8)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c3d0)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (c000000000e8c060)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f324)
Location: include/linux/skbuff.h:3941
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
In net/ipv4/tcp_ipv4.c (ffffffe0007eec1c)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffe0007fb800)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffe00080087c)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffe00080a1d6)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086ce34)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008762c2)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b522)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088da5e)
Location: include/linux/skbuff.h:3941
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
In net/ipv4/tcp_ipv4.c (ffffffff8197b3bc)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8198925a)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8198ee90)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81999e0c)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a0631f)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a100b2)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a26784)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28a3a)
Location: include/linux/skbuff.h:3941
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
In net/ipv4/tcp_ipv4.c (ffffffff81934e7c)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81942d1a)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff81948950)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff819538cc)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c30df)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cce72)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e3544)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5c2a)
Location: include/linux/skbuff.h:3941
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
In net/ipv4/tcp_ipv4.c (ffffffff819e5b8c)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819f3a2a)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff819f9730)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81a046ac)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a70d9f)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7ab32)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a92334)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a945ea)
Location: include/linux/skbuff.h:3941
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
In net/ipv4/tcp_ipv4.c (ffffffff819ef84c)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819fdbea)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff81a03a20)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81a0ec2c)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d3af)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87372)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e3e4)
Location: include/linux/skbuff.h:3941
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa074a)
Location: include/linux/skbuff.h:3941
Inline: True
```
</details>
</li>
</ul>

## Differences
