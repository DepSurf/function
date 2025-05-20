# Function: <code>sock_skb_set_dropcount</code>

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
In net/core/sock.c (ffffffff81702f6f)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/packet/af_packet.c (ffffffff81808c5b)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81768432)
Location: include/net/sock.h:2100
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/packet/af_packet.c (ffffffff8187a2ae)
Location: include/net/sock.h:2100
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81795472)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff81824d57)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff818aeb1e)
Location: include/net/sock.h:2166
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff817b3a2e)
Location: include/net/sock.h:2190
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff8184820b)
Location: include/net/sock.h:2190
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff818d386e)
Location: include/net/sock.h:2190
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff8182d0c3)
Location: include/net/sock.h:2204
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff818c7c5a)
Location: include/net/sock.h:2204
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff81958795)
Location: include/net/sock.h:2204
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81876ea6)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff8191df00)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff819b21e7)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81897646)
Location: include/net/sock.h:2297
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff8194cb50)
Location: include/net/sock.h:2297
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff819e90f8)
Location: include/net/sock.h:2297
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff818e1a86)
Location: include/net/sock.h:2303
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff819b1308)
Location: include/net/sock.h:2303
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff81a57571)
Location: include/net/sock.h:2303
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81913c76)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff819e8034)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff81a8e5ad)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff819e5d88)
Location: include/net/sock.h:2376
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff81ad5f7a)
Location: include/net/sock.h:2376
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff81b8b112)
Location: include/net/sock.h:2376
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff819e585a)
Location: include/net/sock.h:2397
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff81ae255a)
Location: include/net/sock.h:2397
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff81b9a128)
Location: include/net/sock.h:2397
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff819cb96a)
Location: include/net/sock.h:2433
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff81acd47a)
Location: include/net/sock.h:2433
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff81b8909a)
Location: include/net/sock.h:2433
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81a7b020)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff81b8be3a)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff81c551aa)
Location: include/net/sock.h:2492
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81bee644)
Location: include/net/sock.h:2615
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff81d18ae9)
Location: include/net/sock.h:2615
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff81df48fc)
Location: include/net/sock.h:2615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81d9e104)
Location: include/net/sock.h:2661
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff81ee19ac)
Location: include/net/sock.h:2661
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff81fc9b8c)
Location: include/net/sock.h:2661
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81e0c979)
Location: include/net/sock.h:2649
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff81f413ad)
Location: include/net/sock.h:2649
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff8202a4b7)
Location: include/net/sock.h:2649
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81ec92f1)
Location: include/net/sock.h:2639
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff82006ff9)
Location: include/net/sock.h:2639
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff820f9fc2)
Location: include/net/sock.h:2639
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffff800010bad07c)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffff800010c9c568)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffff800010d5b770)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (c0cca3f0)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (c0da7710)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (c0e5b890)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (c000000000c82494)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (c000000000daea50)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (c000000000e95d20)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffe00073f058)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffe0007fa5c0)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffe000892878)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff818b3c76)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff81987ea4)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff81a2dc3d)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff8186dbc6)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff81941964)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff819eae2d)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81904c76)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff819f2674)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff81a997ed)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
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
In net/core/sock.c (ffffffff81925d16)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/udp.c (ffffffff819fc4c5)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/packet/af_packet.c (ffffffff81aa45ed)
Location: include/net/sock.h:2324
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
```
</details>
</li>
</ul>

## Differences
