# Function: <code>__pskb_copy</code>

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
In net/core/skbuff.c (ffffffff817090f5)
Location: include/linux/skbuff.h:871
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff817764e3)
Location: include/linux/skbuff.h:871
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/core/skbuff.c (ffffffff81770955)
Location: include/linux/skbuff.h:968
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff817e5a3c)
Location: include/linux/skbuff.h:968
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff8179dcd5)
Location: include/linux/skbuff.h:983
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81815ea6)
Location: include/linux/skbuff.h:983
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff817bbd95)
Location: include/linux/skbuff.h:960
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81836225)
Location: include/linux/skbuff.h:960
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff81835f55)
Location: include/linux/skbuff.h:1034
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff818b580f)
Location: include/linux/skbuff.h:1034
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff8187fa25)
Location: include/linux/skbuff.h:1039
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff8190aeb5)
Location: include/linux/skbuff.h:1039
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff818a0f85)
Location: include/linux/skbuff.h:1064
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff8193915a)
Location: include/linux/skbuff.h:1064
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff818eb975)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff8199d4b1)
Location: include/linux/skbuff.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff8191dad5)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff819d3f78)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff819f0505)
Location: include/linux/skbuff.h:1144
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81ac07d0)
Location: include/linux/skbuff.h:1144
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff819f00b5)
Location: include/linux/skbuff.h:1160
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81acc21d)
Location: include/linux/skbuff.h:1160
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff819d5df5)
Location: include/linux/skbuff.h:1168
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81ab7408)
Location: include/linux/skbuff.h:1168
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff81a85a45)
Location: include/linux/skbuff.h:1180
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81b74606)
Location: include/linux/skbuff.h:1180
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff81bfa791)
Location: include/linux/skbuff.h:1487
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81d03d52)
Location: include/linux/skbuff.h:1487
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff81daa581)
Location: include/linux/skbuff.h:1331
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81ec8cc0)
Location: include/linux/skbuff.h:1331
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff81e1a0c1)
Location: include/linux/skbuff.h:1350
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81f277e4)
Location: include/linux/skbuff.h:1350
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff81ed7681)
Location: include/linux/skbuff.h:1357
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81fe94c4)
Location: include/linux/skbuff.h:1357
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffff800010bb7c34)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffff800010c86a30)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (c0cd4834)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (c0d95d94)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (c000000000c8fa10)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (c000000000d92ed0)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffe0007475ea)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffe0007e7f96)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff818bdad5)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81973de8)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff81877a15)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff8192d8b8)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff8190ead5)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff819de5b8)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/skbuff.c (ffffffff8192fc05)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff819e8251)
Location: include/linux/skbuff.h:1112
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
</details>
</li>
</ul>

## Differences
