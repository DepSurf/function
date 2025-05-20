# Function: <code>__skb_pagelen</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8183664f)
Location: include/linux/skbuff.h:1884
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff81897fcf)
Location: include/linux/skbuff.h:1884
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff8190b8dc)
Location: include/linux/skbuff.h:1884
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/core/skbuff.c (ffffffff8188068e)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff818ec2ab)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81962c90)
Location: include/linux/skbuff.h:1895
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/core/skbuff.c (ffffffff818a155b)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff81919445)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81997c7f)
Location: include/linux/skbuff.h:1973
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/core/skbuff.c (ffffffff818ebf4b)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff8197b7be)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff81a03d9f)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff81a48634)
Location: include/linux/skbuff.h:2063
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffff8191e07b)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff819b1e7d)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a983)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff81a7f1f5)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffff819f0cdb)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff81a9c714)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ff5d)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff81b79eae)
Location: include/linux/skbuff.h:2100
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffff819f0c45)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff81aa657a)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e9fd)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff81b88dfe)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffff819d6fbb)
Location: include/linux/skbuff.h:2137
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff81a916ea)
Location: include/linux/skbuff.h:2137
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b7c7)
Location: include/linux/skbuff.h:2137
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff81b77c10)
Location: include/linux/skbuff.h:2137
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffff81a875db)
Location: include/linux/skbuff.h:2166
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff81b4caba)
Location: include/linux/skbuff.h:2166
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1881)
Location: include/linux/skbuff.h:2166
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff81c42730)
Location: include/linux/skbuff.h:2166
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffff81bfbb2a)
Location: include/linux/skbuff.h:2517
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff81cda1d5)
Location: include/linux/skbuff.h:2517
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a23f)
Location: include/linux/skbuff.h:2517
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff81de11dc)
Location: include/linux/skbuff.h:2517
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffff81dabcda)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff81e9a995)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff81f581cf)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff81fb363c)
Location: include/linux/skbuff.h:2375
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffff81e1b8ca)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff81ef931f)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7dc1)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff82013d34)
Location: include/linux/skbuff.h:2411
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffff81ed8e8a)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff81fbd23c)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff820853fe)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff820e2e8e)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffff800010bb87a0)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffff800010c63b78)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffff800010cfbad0)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffff800010d4a484)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (c0cd52a8)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (c0d720b0)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (c0e02a54)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (c0e4ba98)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (c000000000c90900)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (c000000000d65d10)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (c000000000e2314c)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (c000000000e80500)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffe000747f5a)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffe0007ca430)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffe0008463ca)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffe000883988)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffff818be07b)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff81951ced)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff819da013)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff81a1e885)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffff81877fbb)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff8190b7dd)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff81996dd3)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff819db645)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffff8190f07b)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff819bc4bd)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff81a44a93)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff81a89305)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/core/skbuff.c (ffffffff819301ab)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/ipv4/ip_output.c (ffffffff819c5dcd)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv6/ip6_output.c (ffffffff81a50753)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
```
In net/ipv6/netfilter.c (ffffffff81a95f65)
Location: include/linux/skbuff.h:2077
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
</details>
</li>
</ul>

## Differences
