# Function: <code>skb_needs_linearize</code>

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
In net/core/dev.c (ffffffff8171c6d9)
Location: include/linux/skbuff.h:2894
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8180377c)
Location: include/linux/skbuff.h:2894
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff8178508b)
Location: include/linux/skbuff.h:3101
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/packet/af_packet.c (ffffffff818749bc)
Location: include/linux/skbuff.h:3101
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b269b)
Location: include/linux/skbuff.h:3153
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cfea0)
Location: include/linux/skbuff.h:3227
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818497ea)
Location: include/linux/skbuff.h:3348
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81893868)
Location: include/linux/skbuff.h:3358
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b4287)
Location: include/linux/skbuff.h:3437
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81900b7d)
Location: include/linux/skbuff.h:3528
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81932ead)
Location: include/linux/skbuff.h:3595
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/skbuff.c (ffffffff819f1822)
Location: include/linux/skbuff.h:3618
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/dev.c (ffffffff81a07d2e)
Location: include/linux/skbuff.h:3618
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/skbuff.c (ffffffff819f1cfb)
Location: include/linux/skbuff.h:3647
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/dev.c (ffffffff81a093fe)
Location: include/linux/skbuff.h:3647
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/skbuff.c (ffffffff819d7b9f)
Location: include/linux/skbuff.h:3711
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/dev.c (ffffffff819efd7e)
Location: include/linux/skbuff.h:3711
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/skbuff.c (ffffffff81a879e4)
Location: include/linux/skbuff.h:3748
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/dev.c (ffffffff81aa11b7)
Location: include/linux/skbuff.h:3748
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/skbuff.c (ffffffff81bfcdd6)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/dev.c (ffffffff81c19067)
Location: include/linux/skbuff.h:4121
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/skbuff.c (ffffffff81dac829)
Location: include/linux/skbuff.h:4017
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/dev.c (ffffffff81dca03d)
Location: include/linux/skbuff.h:4017
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/skbuff.c (ffffffff81e1c624)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/dev.c (ffffffff81e3abb5)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/skbuff.c (ffffffff81ed9d24)
Location: include/linux/skbuff.h:4086
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/dev.c (ffffffff81ef8f59)
Location: include/linux/skbuff.h:4086
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd0e74)
Location: include/linux/skbuff.h:3595
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cebaec)
Location: include/linux/skbuff.h:3595
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caef40)
Location: include/linux/skbuff.h:3595
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075b468)
Location: include/linux/skbuff.h:3595
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d2ead)
Location: include/linux/skbuff.h:3595
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188cd3d)
Location: include/linux/skbuff.h:3595
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81923ead)
Location: include/linux/skbuff.h:3595
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194531d)
Location: include/linux/skbuff.h:3595
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
</ul>

## Differences
