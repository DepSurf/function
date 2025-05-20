# Function: <code>__skb_dst_copy</code>

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
Location: include/net/dst.h:298
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff8175c5a8)
Location: include/net/dst.h:298
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
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff817c93a8)
Location: include/net/dst.h:295
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
Location: include/net/dst.h:295
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff817f8f48)
Location: include/net/dst.h:295
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
Location: include/net/dst.h:301
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81819368)
Location: include/net/dst.h:301
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
Location: include/net/dst.h:304
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81897928)
Location: include/net/dst.h:304
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
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff818ebc38)
Location: include/net/dst.h:287
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
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81918f08)
Location: include/net/dst.h:287
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
Location: include/net/dst.h:276
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff8197b024)
Location: include/net/dst.h:276
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
Location: include/net/dst.h:276
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff819b1994)
Location: include/net/dst.h:276
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
In net/core/skbuff.c (ffffffff819ec828)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/route.c (ffffffff81a957a9)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81a9c1d8)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b3168d)
Location: include/net/dst.h:275
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
In net/core/skbuff.c (ffffffff819ec4e8)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81a6f3df)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81a9f839)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81aa6038)
Location: include/net/dst.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b4027d)
Location: include/net/dst.h:275
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
In net/core/skbuff.c (ffffffff819d29d8)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81a57cb2)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81a8a779)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81a911f8)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e88d)
Location: include/net/dst.h:278
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
In net/core/skbuff.c (ffffffff81a8262f)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81b10c5b)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81b45641)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81b4c56f)
Location: include/net/dst.h:278
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4c3a)
Location: include/net/dst.h:278
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
In net/core/skbuff.c (ffffffff81bf701f)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81c97ddc)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81cd235e)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81cd9bbf)
Location: include/net/dst.h:279
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81d8da5b)
Location: include/net/dst.h:279
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
In net/core/skbuff.c (ffffffff81da5f8f)
Location: include/net/dst.h:273
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81e53d7c)
Location: include/net/dst.h:273
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81e9298e)
Location: include/net/dst.h:273
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81e9a34f)
Location: include/net/dst.h:273
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bb8b)
Location: include/net/dst.h:273
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
In net/core/skbuff.c (ffffffff81e1507f)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81eaf5fc)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81ef112f)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81ef8caf)
Location: include/net/dst.h:287
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb94b)
Location: include/net/dst.h:287
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
In net/core/skbuff.c (ffffffff81ed241f)
Location: include/net/dst.h:280
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/sched/sch_frag.c (ffffffff81f7207c)
Location: include/net/dst.h:280
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/ipv4/route.c (ffffffff81fb527f)
Location: include/net/dst.h:280
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_use_hint
```
```
In net/ipv4/ip_output.c (ffffffff81fbcbcf)
Location: include/net/dst.h:280
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff82088d82)
Location: include/net/dst.h:280
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
Location: include/net/dst.h:276
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffff800010c62350)
Location: include/net/dst.h:276
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
In net/core/skbuff.c (c0cd0538)
Location: include/net/dst.h:276
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (c0d71b3c)
Location: include/net/dst.h:276
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
Location: include/net/dst.h:276
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (c000000000d6560c)
Location: include/net/dst.h:276
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
Location: include/net/dst.h:276
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffe0007c9f14)
Location: include/net/dst.h:276
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
Location: include/net/dst.h:276
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff81951804)
Location: include/net/dst.h:276
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
Location: include/net/dst.h:276
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff8190b2f4)
Location: include/net/dst.h:276
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
Location: include/net/dst.h:276
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff819bbfd4)
Location: include/net/dst.h:276
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
Location: include/net/dst.h:276
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff819c58e4)
Location: include/net/dst.h:276
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
</details>
</li>
</ul>

## Differences
