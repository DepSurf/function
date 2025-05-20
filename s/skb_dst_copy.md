# Function: <code>skb_dst_copy</code>

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
In net/core/skbuff.c (ffffffff81705bbd)
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff8175c5a8)
Location: include/net/dst.h:305
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffff8176c88d)
Location: include/net/dst.h:302
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff817c93a8)
Location: include/net/dst.h:302
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffff81799a5d)
Location: include/net/dst.h:302
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff817f8f48)
Location: include/net/dst.h:302
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffff817b8ecd)
Location: include/net/dst.h:308
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81819368)
Location: include/net/dst.h:308
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffff8183188d)
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81897928)
Location: include/net/dst.h:311
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffff8187bd7d)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff818ebc38)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffff8189bfdd)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81918f08)
Location: include/net/dst.h:294
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffff818e6895)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff8197b024)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffff819189dd)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff819b1994)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffff819ec824)
Location: include/net/dst.h:282
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/route.c (ffffffff81a957a9)
Location: include/net/dst.h:282
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81a9c1d3)
Location: include/net/dst.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b31689)
Location: include/net/dst.h:282
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
In net/core/skbuff.c (ffffffff819ec4e4)
Location: include/net/dst.h:282
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/route.c (ffffffff81a9f839)
Location: include/net/dst.h:282
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81aa6033)
Location: include/net/dst.h:282
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b40279)
Location: include/net/dst.h:282
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
In net/core/skbuff.c (ffffffff819d29d4)
Location: include/net/dst.h:285
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/route.c (ffffffff81a8a779)
Location: include/net/dst.h:285
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81a911f3)
Location: include/net/dst.h:285
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e889)
Location: include/net/dst.h:285
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
In net/core/skbuff.c (ffffffff81a82624)
Location: include/net/dst.h:286
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/route.c (ffffffff81b45641)
Location: include/net/dst.h:286
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81b4c563)
Location: include/net/dst.h:286
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4c2d)
Location: include/net/dst.h:286
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
In net/core/skbuff.c (ffffffff81bf7014)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/route.c (ffffffff81cd235e)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81cd9bb3)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81d8da4e)
Location: include/net/dst.h:287
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
In net/core/skbuff.c (ffffffff81da5f84)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/route.c (ffffffff81e9298e)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81e9a343)
Location: include/net/dst.h:281
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bb7e)
Location: include/net/dst.h:281
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
In net/core/skbuff.c (ffffffff81e15074)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/route.c (ffffffff81ef112f)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81ef8ca3)
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb93e)
Location: include/net/dst.h:295
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
In net/core/skbuff.c (ffffffff81ed2414)
Location: include/net/dst.h:288
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/route.c (ffffffff81fb527f)
Location: include/net/dst.h:288
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81fbcbc3)
Location: include/net/dst.h:288
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff82088d75)
Location: include/net/dst.h:288
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
In net/core/skbuff.c (ffff800010bb4788)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffff800010c62350)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (c0cd0534)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (c0d71b38)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (c000000000c87a7c)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (c000000000d6560c)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffe0007424fa)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffe0007c9f14)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffff818b89dd)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81951804)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffff8187292d)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff8190b2f4)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffff819099dd)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff819bbfd4)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
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
In net/core/skbuff.c (ffffffff8192aadd)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff819c58e4)
Location: include/net/dst.h:283
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
</details>
</li>
</ul>

## Differences
