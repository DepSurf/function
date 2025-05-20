# Function: <code>__skb_dequeue_tail</code>

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
In net/core/skbuff.c (ffffffff81704f3d)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/sched/sch_fifo.c (ffffffff81749015)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_queue_drop
```
```
In net/ipv4/ip_output.c (ffffffff8175debf)
Location: include/linux/skbuff.h:1674
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c49e3)
Location: include/linux/skbuff.h:1674
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff8176bb0d)
Location: include/linux/skbuff.h:1775
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff817ca11f)
Location: include/linux/skbuff.h:1775
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81831ab3)
Location: include/linux/skbuff.h:1775
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff81798bdd)
Location: include/linux/skbuff.h:1790
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff817f93df)
Location: include/linux/skbuff.h:1790
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff818634e3)
Location: include/linux/skbuff.h:1790
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff817b718d)
Location: include/linux/skbuff.h:1783
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff8181981f)
Location: include/linux/skbuff.h:1783
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81887ba3)
Location: include/linux/skbuff.h:1783
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff8182f78d)
Location: include/linux/skbuff.h:1865
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff81897e4f)
Location: include/linux/skbuff.h:1865
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81908e63)
Location: include/linux/skbuff.h:1865
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff81879cad)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff818ec9e5)
Location: include/linux/skbuff.h:1876
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81960125)
Location: include/linux/skbuff.h:1876
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff8189a91d)
Location: include/linux/skbuff.h:1954
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff81919f85)
Location: include/linux/skbuff.h:1954
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81994f05)
Location: include/linux/skbuff.h:1954
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff818e4f44)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff8197bbd5)
Location: include/linux/skbuff.h:2043
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a009a5)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff819170d4)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff819b2575)
Location: include/linux/skbuff.h:2057
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a37575)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff819e9a54)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff81a9bc75)
Location: include/linux/skbuff.h:2080
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ca95)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff819e97f4)
Location: include/linux/skbuff.h:2101
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff81aa5ad5)
Location: include/linux/skbuff.h:2101
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b4b9)
Location: include/linux/skbuff.h:2101
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
```
```
In net/mptcp/protocol.c (ffffffff81bbc5d8)
Location: include/linux/skbuff.h:2101
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
In net/core/skbuff.c (ffffffff819cf914)
Location: include/linux/skbuff.h:2117
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff81a909d5)
Location: include/linux/skbuff.h:2117
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b28c38)
Location: include/linux/skbuff.h:2117
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
```
```
In net/mptcp/protocol.c (ffffffff81baf7f6)
Location: include/linux/skbuff.h:2117
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/core/skbuff.c (ffffffff81a7f464)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff81b4bb55)
Location: include/linux/skbuff.h:2146
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81beeb28)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff81bf3794)
Location: include/linux/skbuff.h:2497
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff81cd9245)
Location: include/linux/skbuff.h:2497
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81d871a8)
Location: include/linux/skbuff.h:2497
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff81da1514)
Location: include/linux/skbuff.h:2355
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff81e99985)
Location: include/linux/skbuff.h:2355
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81f54cc8)
Location: include/linux/skbuff.h:2355
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff81e0fe04)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff81ef82f5)
Location: include/linux/skbuff.h:2391
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb46d8)
Location: include/linux/skbuff.h:2391
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff81ecc8b4)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff81fbc215)
Location: include/linux/skbuff.h:2398
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff82081f88)
Location: include/linux/skbuff.h:2398
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffff800010bb3cbc)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffff800010c620e4)
Location: include/linux/skbuff.h:2057
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cf8c14)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (c0ccdaec)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (c0d72804)
Location: include/linux/skbuff.h:2057
Inline: True
```
```
In net/ipv6/ip6_output.c (c0dfea80)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (c000000000c861d4)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (c000000000d66754)
Location: include/linux/skbuff.h:2057
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e1f07c)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffe00074152e)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffe0007cab06)
Location: include/linux/skbuff.h:2057
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe0008435da)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff818b70d4)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff819523e5)
Location: include/linux/skbuff.h:2057
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d6c05)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff81871024)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff8190bed5)
Location: include/linux/skbuff.h:2057
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819939c5)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff819080d4)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff819bcbb5)
Location: include/linux/skbuff.h:2057
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a41685)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
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
In net/core/skbuff.c (ffffffff81929114)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dequeue_tail
```
```
In net/ipv4/ip_output.c (ffffffff819c64c5)
Location: include/linux/skbuff.h:2057
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d2e5)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
```
</details>
</li>
</ul>

## Differences
