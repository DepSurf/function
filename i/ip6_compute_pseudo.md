# Function: <code>ip6_compute_pseudo</code>

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
In net/ipv6/udp.c (ffffffff817e4d53)
Location: include/net/ip6_checksum.h:44
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff817e865a)
Location: include/net/ip6_checksum.h:44
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f1b7b)
Location: include/net/ip6_checksum.h:44
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818002c8)
Location: include/net/ip6_checksum.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff818025da)
Location: include/net/ip6_checksum.h:44
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
In net/ipv6/udp.c (ffffffff81852a7d)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81856e0d)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818603e0)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81871946)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff818738dd)
Location: include/net/ip6_checksum.h:43
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
In net/ipv6/udp.c (ffffffff8188477d)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888c0d)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892370)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5ea6)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a7f5d)
Location: include/net/ip6_checksum.h:43
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
In net/ipv6/udp.c (ffffffff818aaf4e)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af29f)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b89cf)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc927)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce7b9)
Location: include/net/ip6_checksum.h:43
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
In net/ipv6/udp.c (ffffffff8192dacb)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/icmp.c (ffffffff81931faf)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b881)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819516de)
Location: include/net/ip6_checksum.h:43
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81953669)
Location: include/net/ip6_checksum.h:43
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
In net/ipv6/udp.c (ffffffff81984e39)
Location: include/net/ip6_checksum.h:43
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff8198aa7f)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994b11)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aabf2)
Location: include/net/ip6_checksum.h:43
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad07d)
Location: include/net/ip6_checksum.h:43
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
In net/ipv6/udp.c (ffffffff819bb5c5)
Location: include/net/ip6_checksum.h:43
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c1343)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb405)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e16e3)
Location: include/net/ip6_checksum.h:43
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3a2d)
Location: include/net/ip6_checksum.h:43
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
In net/ipv6/udp.c (ffffffff81a2a1b7)
Location: include/net/ip6_checksum.h:39
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a30115)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39e58)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a504a1)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a52799)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffff81a60d07)
Location: include/net/ip6_checksum.h:39
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a66c65)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a709e8)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a870c1)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a89379)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffff81b59c5b)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/icmp.c (ffffffff81b5f695)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a169)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b82374)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84809)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffff81b682bb)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/icmp.c (ffffffff81b6de35)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78c4a)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91a68)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b94169)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffff81b565c7)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/icmp.c (ffffffff81b5c1b8)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6779c)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80cb9)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b83279)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffff81c1cf97)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/icmp.c (ffffffff81c2391f)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f3cc)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4ccd9)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f349)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffff81db9874)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/icmp.c (ffffffff81dc0849)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc82d)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded150)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defd5d)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffff81f898f4)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/icmp.c (ffffffff81f90fd0)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d96c)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc0f60)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3e6d)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffff81fe89c5)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/icmp.c (ffffffff81ff18c0)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe3ec)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff82021ef0)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024e8d)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffff820b7525)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/icmp.c (ffffffff820bf4bf)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd2ce)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f1010)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f416d)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffff800010d26988)
Location: include/net/ip6_checksum.h:39
Inline: True
```
```
In net/ipv6/icmp.c (ffff800010d2cbb0)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38ec8)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffff800010d53820)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffff800010d56194)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (c0e29fc8)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/icmp.c (c0e30a88)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e3ba68)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (c0e54100)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (c0e5678c)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (c000000000e566f0)
Location: include/net/ip6_checksum.h:39
Inline: True
```
```
In net/ipv6/icmp.c (c000000000e5e67c)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c39c)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (c000000000e8c028)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f2e8)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffe000867116)
Location: include/net/ip6_checksum.h:39
Inline: True
```
```
In net/ipv6/icmp.c (ffffffe00086ce20)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008762a6)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b500)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088da42)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffff81a00397)
Location: include/net/ip6_checksum.h:39
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a062f5)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10078)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a26751)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28a09)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffff819bd157)
Location: include/net/ip6_checksum.h:39
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c30b5)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cce38)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e3511)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5bf9)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffff81a6ae17)
Location: include/net/ip6_checksum.h:39
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a70d75)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7aaf8)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a92301)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a945b9)
Location: include/net/ip6_checksum.h:39
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
In net/ipv6/udp.c (ffffffff81a77427)
Location: include/net/ip6_checksum.h:39
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a7d385)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87338)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e3b1)
Location: include/net/ip6_checksum.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0719)
Location: include/net/ip6_checksum.h:39
Inline: True
```
</details>
</li>
</ul>

## Differences
