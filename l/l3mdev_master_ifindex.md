# Function: <code>l3mdev_master_ifindex</code>

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
In net/ipv4/route.c (ffffffff81753471)
Location: include/net/l3mdev.h:43
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/icmp.c (ffffffff8178e0bf)
Location: include/net/l3mdev.h:43
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv6/icmp.c (ffffffff817e7bd2)
Location: include/net/l3mdev.h:43
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff817bf6f1)
Location: include/net/l3mdev.h:53
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/icmp.c (ffffffff817fb7b6)
Location: include/net/l3mdev.h:53
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv6/icmp.c (ffffffff81855d0e)
Location: include/net/l3mdev.h:53
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff817ef041)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/icmp.c (ffffffff8182c684)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/netfilter.c (ffffffff8184aeb7)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/icmp.c (ffffffff81887b47)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff8180f129)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181da14)
Location: include/net/l3mdev.h:50
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8184d85d)
Location: include/net/l3mdev.h:50
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff8186e907)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/icmp.c (ffffffff818ae12f)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff8188e789)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189c98d)
Location: include/net/l3mdev.h:50
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff818cd58d)
Location: include/net/l3mdev.h:50
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff818ef2c7)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/icmp.c (ffffffff81930daf)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff818e240a)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f0e73)
Location: include/net/l3mdev.h:50
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8192394a)
Location: include/net/l3mdev.h:50
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81945c6d)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/icmp.c (ffffffff81989aa6)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff8190f2aa)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191e9ac)
Location: include/net/l3mdev.h:50
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81952742)
Location: include/net/l3mdev.h:50
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81975f8d)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff819aa8b9)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff819c037d)
Location: include/net/l3mdev.h:50
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff81970ec1)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981127)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819b7002)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff819dfb29)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81a17d0a)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff81a2f1b9)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff819a78c1)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b6c3a)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819edd02)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81a16b59)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81a4e95a)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff81a65d09)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff81a90bb4)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa1492)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81adbaf9)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81b07b8c)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81b4628a)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff81b5e951)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff81a9aa04)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aac7bb)
Location: include/net/l3mdev.h:65
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ae86ef)
Location: include/net/l3mdev.h:65
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81b15f66)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81b54dbe)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff81b6d0f9)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff81a85d9a)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a979f7)
Location: include/net/l3mdev.h:65
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ad4598)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/netfilter.c (ffffffff81b03dc7)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81b4284e)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff81b5b44f)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff81b4059a)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b52e8e)
Location: include/net/l3mdev.h:65
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b93fad)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/netfilter.c (ffffffff81bc60a0)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81c07f9e)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff81c22b68)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff81cccffe)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ce0d09)
Location: include/net/l3mdev.h:65
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81d2543f)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/netfilter.c (ffffffff81d5b27c)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81da2caf)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff81dbf65c)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/netfilter.c (ffffffff81de0b96)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/route.c (ffffffff81e8d0ae)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1101)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/ipv4/icmp.c (ffffffff81eeca2f)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/netfilter.c (ffffffff81f2570c)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81f7209f)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff81f8fdab)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/netfilter.c (ffffffff81fb2fd6)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/route.c (ffffffff81eeb7df)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff81eff8ad)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/ipv4/icmp.c (ffffffff81f4b61b)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmpv4_xrlim_allow
```
```
In net/ipv4/netfilter.c (ffffffff81f8529c)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81fd218f)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff81ff05ed)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/netfilter.c (ffffffff820136c6)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/route.c (ffffffff81faf7ef)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc3b3d)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/ipv4/icmp.c (ffffffff8201172b)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmpv4_xrlim_allow
```
```
In net/ipv4/netfilter.c (ffffffff8204b957)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff8209f71f)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff820be1be)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/netfilter.c (ffffffff820e282f)
Location: include/net/l3mdev.h:65
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/route.c (ffff800010c59c44)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffff800010c68d80)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/icmp.c (ffff800010ca388c)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/netfilter.c (ffff800010cd27a8)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffff800010d13344)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffff800010d2bbf0)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (c0d66ca0)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (c0d78050)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/icmp.c (c0db052c)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/netfilter.c (c0ddc6dc)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (c0e18480)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (c0e2fbec)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (c000000000d5852c)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (c000000000d6d7bc)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/icmp.c (c000000000db70c8)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/netfilter.c (c000000000df0e14)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (c000000000e3ecb8)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (c000000000e5d4d0)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffe0007c1434)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cee74)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/icmp.c (ffffffe0007ff6c0)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffe000823ada)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffe000858ae0)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffe00086c040)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff81947731)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff81956aaa)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8198daa2)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff819b61e9)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff819edfea)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff81a05399)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff81901221)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191059a)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81947562)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81972fd9)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff819aadaa)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff819c2159)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff819b1f01)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c127a)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819f8342)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81a20a89)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81a58a6a)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff81a6fe19)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv4/route.c (ffffffff819bb5a9)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cac5a)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81a02649)
Location: include/net/l3mdev.h:46
Inline: True
```
```
In net/ipv4/netfilter.c (ffffffff81a2bfa9)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/ipv6/route.c (ffffffff81a64c30)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffff81a7c43a)
Location: include/net/l3mdev.h:46
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
</details>
</li>
</ul>

## Differences
