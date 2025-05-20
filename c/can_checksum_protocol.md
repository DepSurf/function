# Function: <code>can_checksum_protocol</code>

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
In net/core/skbuff.c (ffffffff8170af5d)
Location: include/linux/netdevice.h:3688
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8171c41f)
Location: include/linux/netdevice.h:3688
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81772755)
Location: include/linux/netdevice.h:3944
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81784d8e)
Location: include/linux/netdevice.h:3944
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff8179f84f)
Location: include/linux/netdevice.h:3911
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817b23d8)
Location: include/linux/netdevice.h:3911
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff817be8a4)
Location: include/linux/netdevice.h:3963
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817cfbe3)
Location: include/linux/netdevice.h:3963
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff818381a4)
Location: include/linux/netdevice.h:3997
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81849536)
Location: include/linux/netdevice.h:3997
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81882703)
Location: include/linux/netdevice.h:4103
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818934f5)
Location: include/linux/netdevice.h:4103
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff818a31ad)
Location: include/linux/netdevice.h:4339
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818b3f23)
Location: include/linux/netdevice.h:4339
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff818ede68)
Location: include/linux/netdevice.h:4360
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81900778)
Location: include/linux/netdevice.h:4360
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff8191ff5a)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81932aa8)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff819f3556)
Location: include/linux/netdevice.h:4565
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a079bf)
Location: include/linux/netdevice.h:4565
Inline: True
Inline callers:
  - net/core/dev.c:harmonize_features
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
In net/core/skbuff.c (ffffffff819f3580)
Location: include/linux/netdevice.h:4771
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a0903a)
Location: include/linux/netdevice.h:4771
Inline: True
Inline callers:
  - net/core/dev.c:harmonize_features
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
In net/core/skbuff.c (ffffffff819d97d4)
Location: include/linux/netdevice.h:4902
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff819efa51)
Location: include/linux/netdevice.h:4902
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81a8978e)
Location: include/linux/netdevice.h:4950
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81aa0e71)
Location: include/linux/netdevice.h:4950
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81bfeaf0)
Location: include/linux/netdevice.h:4767
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81c18d5d)
Location: include/linux/netdevice.h:4767
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81dad53b)
Location: include/linux/netdevice.h:4811
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81dc9d27)
Location: include/linux/netdevice.h:4811
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81e1d428)
Location: include/linux/netdevice.h:4858
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81e3a88a)
Location: include/linux/netdevice.h:4858
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81edab21)
Location: include/linux/netdevice.h:4934
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81ef8c5c)
Location: include/linux/netdevice.h:4934
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffff800010bba9f0)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffff800010bd0b34)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (c0cd7170)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c0ceb71c)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (c000000000c936bc)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c000000000caead4)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffe000749bd2)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffe00075b1ea)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff818bff5a)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818d2aa8)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81879e9a)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8188c938)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff81910f5a)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81923aa8)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
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
In net/core/skbuff.c (ffffffff819320ba)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81944f18)
Location: include/linux/netdevice.h:4373
Inline: True
Inline callers:
  - net/core/dev.c:netif_skb_features
```
</details>
</li>
</ul>

## Differences
