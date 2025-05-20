# Function: <code>__skb_checksum_validate_needed</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177e42d)
Location: include/linux/skbuff.h:3135
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8178a095)
Location: include/linux/skbuff.h:3135
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8178f0e1)
Location: include/linux/skbuff.h:3135
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81797600)
Location: include/linux/skbuff.h:3135
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff817e8625)
Location: include/linux/skbuff.h:3135
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f1b4d)
Location: include/linux/skbuff.h:3135
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81800233)
Location: include/linux/skbuff.h:3135
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff818025a5)
Location: include/linux/skbuff.h:3135
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
In net/ipv4/tcp_ipv4.c (ffffffff817eb83b)
Location: include/linux/skbuff.h:3342
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff817f73d3)
Location: include/linux/skbuff.h:3342
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff817fc741)
Location: include/linux/skbuff.h:3342
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81805eb6)
Location: include/linux/skbuff.h:3342
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81856dc5)
Location: include/linux/skbuff.h:3342
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818603ab)
Location: include/linux/skbuff.h:3342
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818718bb)
Location: include/linux/skbuff.h:3342
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff818738a0)
Location: include/linux/skbuff.h:3342
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
In net/ipv4/tcp_ipv4.c (ffffffff8181c1ab)
Location: include/linux/skbuff.h:3394
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff818282f5)
Location: include/linux/skbuff.h:3394
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8182d6a1)
Location: include/linux/skbuff.h:3394
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81836f36)
Location: include/linux/skbuff.h:3394
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888bc5)
Location: include/linux/skbuff.h:3394
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8189233b)
Location: include/linux/skbuff.h:3394
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5e1b)
Location: include/linux/skbuff.h:3394
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a7f20)
Location: include/linux/skbuff.h:3394
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
In net/ipv4/tcp_ipv4.c (ffffffff8183c97b)
Location: include/linux/skbuff.h:3447
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81849691)
Location: include/linux/skbuff.h:3447
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8184eb40)
Location: include/linux/skbuff.h:3447
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff818583ff)
Location: include/linux/skbuff.h:3447
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af255)
Location: include/linux/skbuff.h:3447
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b899a)
Location: include/linux/skbuff.h:3447
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc87d)
Location: include/linux/skbuff.h:3447
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce780)
Location: include/linux/skbuff.h:3447
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
In net/ipv4/tcp_ipv4.c (ffffffff818bc0cc)
Location: include/linux/skbuff.h:3631
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff818c90b0)
Location: include/linux/skbuff.h:3631
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff818ce8c0)
Location: include/linux/skbuff.h:3631
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff818d82cf)
Location: include/linux/skbuff.h:3631
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81931f65)
Location: include/linux/skbuff.h:3631
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b84c)
Location: include/linux/skbuff.h:3631
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff8195162b)
Location: include/linux/skbuff.h:3631
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81953630)
Location: include/linux/skbuff.h:3631
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
In net/ipv4/tcp_ipv4.c (ffffffff81911b11)
Location: include/linux/skbuff.h:3641
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8191f1b8)
Location: include/linux/skbuff.h:3641
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff81924cec)
Location: include/linux/skbuff.h:3641
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8192ecd0)
Location: include/linux/skbuff.h:3641
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198aa6d)
Location: include/linux/skbuff.h:3641
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994b03)
Location: include/linux/skbuff.h:3641
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aabd7)
Location: include/linux/skbuff.h:3641
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad05c)
Location: include/linux/skbuff.h:3641
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
In net/ipv4/tcp_ipv4.c (ffffffff819402e5)
Location: include/linux/skbuff.h:3726
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8194de12)
Location: include/linux/skbuff.h:3726
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff81953afb)
Location: include/linux/skbuff.h:3726
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff8195e127)
Location: include/linux/skbuff.h:3726
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c1331)
Location: include/linux/skbuff.h:3726
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb3f7)
Location: include/linux/skbuff.h:3726
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e16c4)
Location: include/linux/skbuff.h:3726
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3a0c)
Location: include/linux/skbuff.h:3726
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
In net/ipv4/tcp_ipv4.c (ffffffff819a481a)
Location: include/linux/skbuff.h:3835
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819b25fd)
Location: include/linux/skbuff.h:3835
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff819b83de)
Location: include/linux/skbuff.h:3835
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff819c34be)
Location: include/linux/skbuff.h:3835
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a30101)
Location: include/linux/skbuff.h:3835
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39e4a)
Location: include/linux/skbuff.h:3835
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a50482)
Location: include/linux/skbuff.h:3835
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a52784)
Location: include/linux/skbuff.h:3835
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
In net/ipv4/tcp_ipv4.c (ffffffff819db51a)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819e939d)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff819ef0de)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff819fa05e)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a66c51)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a709da)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a870a2)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a89364)
Location: include/linux/skbuff.h:3902
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
In net/ipv4/tcp_ipv4.c (ffffffff81ac85bf)
Location: include/linux/skbuff.h:3936
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ad31ed)
Location: include/linux/skbuff.h:3936
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81add02e)
Location: include/linux/skbuff.h:3936
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ae88f0)
Location: include/linux/skbuff.h:3936
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5f681)
Location: include/linux/skbuff.h:3936
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a157)
Location: include/linux/skbuff.h:3936
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b82355)
Location: include/linux/skbuff.h:3936
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b847f4)
Location: include/linux/skbuff.h:3936
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
In net/ipv4/tcp_ipv4.c (ffffffff81ad455f)
Location: include/linux/skbuff.h:3965
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81adf5ef)
Location: include/linux/skbuff.h:3965
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81ae9d7e)
Location: include/linux/skbuff.h:3965
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81af57f0)
Location: include/linux/skbuff.h:3965
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6de21)
Location: include/linux/skbuff.h:3965
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78c38)
Location: include/linux/skbuff.h:3965
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91a49)
Location: include/linux/skbuff.h:3965
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b94154)
Location: include/linux/skbuff.h:3965
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
In net/ipv4/tcp_ipv4.c (ffffffff81abf621)
Location: include/linux/skbuff.h:4029
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81aca4f6)
Location: include/linux/skbuff.h:4029
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81ad54d8)
Location: include/linux/skbuff.h:4029
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ae0f50)
Location: include/linux/skbuff.h:4029
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c1a4)
Location: include/linux/skbuff.h:4029
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6778a)
Location: include/linux/skbuff.h:4029
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80c8f)
Location: include/linux/skbuff.h:4029
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b83264)
Location: include/linux/skbuff.h:4029
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
In net/ipv4/tcp_ipv4.c (ffffffff81b7d169)
Location: include/linux/skbuff.h:4066
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81b88dd6)
Location: include/linux/skbuff.h:4066
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81b942de)
Location: include/linux/skbuff.h:4066
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81ba05f0)
Location: include/linux/skbuff.h:4066
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c2390b)
Location: include/linux/skbuff.h:4066
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f3ba)
Location: include/linux/skbuff.h:4066
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4ccaf)
Location: include/linux/skbuff.h:4066
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f334)
Location: include/linux/skbuff.h:4066
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
In net/ipv4/tcp_ipv4.c (ffffffff81d0d0da)
Location: include/linux/skbuff.h:4485
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81d1a846)
Location: include/linux/skbuff.h:4485
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81d25bad)
Location: include/linux/skbuff.h:4485
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81d32ac5)
Location: include/linux/skbuff.h:4485
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc0835)
Location: include/linux/skbuff.h:4485
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc810)
Location: include/linux/skbuff.h:4485
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded11f)
Location: include/linux/skbuff.h:4485
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defd44)
Location: include/linux/skbuff.h:4485
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
In net/ipv4/tcp_ipv4.c (ffffffff81ed2b54)
Location: include/linux/skbuff.h:4381
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ee1576)
Location: include/linux/skbuff.h:4381
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81eed50f)
Location: include/linux/skbuff.h:4381
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81efad55)
Location: include/linux/skbuff.h:4381
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81f90fbe)
Location: include/linux/skbuff.h:4381
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d94f)
Location: include/linux/skbuff.h:4381
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc0f2f)
Location: include/linux/skbuff.h:4381
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3e54)
Location: include/linux/skbuff.h:4381
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
In net/ipv4/tcp_ipv4.c (ffffffff81f3183b)
Location: include/linux/skbuff.h:4413
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81f40fb6)
Location: include/linux/skbuff.h:4413
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff81f4cecf)
Location: include/linux/skbuff.h:4413
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81f5a7f5)
Location: include/linux/skbuff.h:4413
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81ff18ae)
Location: include/linux/skbuff.h:4413
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe3cf)
Location: include/linux/skbuff.h:4413
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff82021ebf)
Location: include/linux/skbuff.h:4413
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024e74)
Location: include/linux/skbuff.h:4413
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
In net/ipv4/tcp_ipv4.c (ffffffff81ff7a36)
Location: include/linux/skbuff.h:4453
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff82006c06)
Location: include/linux/skbuff.h:4453
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv4/icmp.c (ffffffff82012fdf)
Location: include/linux/skbuff.h:4453
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff82020d35)
Location: include/linux/skbuff.h:4453
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff820bf4ad)
Location: include/linux/skbuff.h:4453
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd2b1)
Location: include/linux/skbuff.h:4453
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f0fdf)
Location: include/linux/skbuff.h:4453
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f4154)
Location: include/linux/skbuff.h:4453
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
In net/ipv4/tcp_ipv4.c (ffff800010c8e8d4)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffff800010c9ec80)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffff800010ca4ec4)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffff800010cb1778)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2cb9c)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38ea4)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffff800010d53800)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffff800010d56170)
Location: include/linux/skbuff.h:3902
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
In net/ipv4/tcp_ipv4.c (c0d9d834)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (c0dabee4)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (c0db17d4)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (c0dbd350)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (c0e30a70)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3ba50)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (c0e540dc)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (c0e56770)
Location: include/linux/skbuff.h:3902
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
In net/ipv4/tcp_ipv4.c (c000000000d9d310)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (c000000000db14d0)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (c000000000db8bd8)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (c000000000dc85f8)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (c000000000e5e66c)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c38c)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (c000000000e8c004)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f2d4)
Location: include/linux/skbuff.h:3902
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
In net/ipv4/tcp_ipv4.c (ffffffe0007eebde)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffe0007fb7c0)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffe000800856)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffe00080a1b8)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086cde8)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876286)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b4da)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088da22)
Location: include/linux/skbuff.h:3902
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
In net/ipv4/tcp_ipv4.c (ffffffff8197b38a)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8198920d)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8198ee7e)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81999dfe)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a062e1)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a1006a)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a26732)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a289f4)
Location: include/linux/skbuff.h:3902
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
In net/ipv4/tcp_ipv4.c (ffffffff81934e4a)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81942ccd)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff8194893e)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff819538be)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c30a1)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cce2a)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e34f2)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5be4)
Location: include/linux/skbuff.h:3902
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
In net/ipv4/tcp_ipv4.c (ffffffff819e5b5a)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819f39dd)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff819f971e)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81a0469e)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a70d61)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7aaea)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a922e2)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a945a4)
Location: include/linux/skbuff.h:3902
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
In net/ipv4/tcp_ipv4.c (ffffffff819ef81a)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819fdb9d)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff81a03a0e)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/igmp.c (ffffffff81a0ec1e)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d371)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a8732a)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e392)
Location: include/linux/skbuff.h:3902
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0704)
Location: include/linux/skbuff.h:3902
Inline: True
```
</details>
</li>
</ul>

## Differences
