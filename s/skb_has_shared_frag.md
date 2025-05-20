# Function: <code>skb_has_shared_frag</code>

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
In net/core/dev.c (ffffffff81718ce6)
Location: include/linux/skbuff.h:2688
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/ipv4/gre_offload.c (ffffffff817a53d5)
Location: include/linux/skbuff.h:2688
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
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
In net/core/skbuff.c (ffffffff81772d5e)
Location: include/linux/skbuff.h:2831
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81780596)
Location: include/linux/skbuff.h:2831
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff8179ff02)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817adee6)
Location: include/linux/skbuff.h:2869
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff817bec6d)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817caa76)
Location: include/linux/skbuff.h:2935
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff81838754)
Location: include/linux/skbuff.h:3034
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818460e0)
Location: include/linux/skbuff.h:3034
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff81882afc)
Location: include/linux/skbuff.h:3046
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8188f590)
Location: include/linux/skbuff.h:3046
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff818a356d)
Location: include/linux/skbuff.h:3122
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818aedb0)
Location: include/linux/skbuff.h:3122
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff818ee29e)
Location: include/linux/skbuff.h:3209
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818fbd80)
Location: include/linux/skbuff.h:3209
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff81920392)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8192e320)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff819f39a5)
Location: include/linux/skbuff.h:3298
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a028ee)
Location: include/linux/skbuff.h:3298
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff819f39cc)
Location: include/linux/skbuff.h:3324
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a0316e)
Location: include/linux/skbuff.h:3324
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff819d9bc4)
Location: include/linux/skbuff.h:3388
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff819e992e)
Location: include/linux/skbuff.h:3388
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff81a89bc6)
Location: include/linux/skbuff.h:3425
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a9a5ae)
Location: include/linux/skbuff.h:3425
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff81bfef2d)
Location: include/linux/skbuff.h:3794
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81c18920)
Location: include/linux/skbuff.h:3794
Inline: True
Inline callers:
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff81dada13)
Location: include/linux/skbuff.h:3690
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81dc98c0)
Location: include/linux/skbuff.h:3690
Inline: True
Inline callers:
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff81e1d995)
Location: include/linux/skbuff.h:3724
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81e3a3d0)
Location: include/linux/skbuff.h:3724
Inline: True
Inline callers:
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff81edb0a2)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81ef8760)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/dev.c:skb_crc32c_csum_help
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffff800010bbad80)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffff800010bc990c)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (c0cd75a4)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c0ce7b44)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (c000000000c93b24)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c000000000ca75cc)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffe000749f16)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffe000756fb8)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff818c0392)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818ce320)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff8187a2d2)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81888440)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff81911392)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8191f320)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
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
In net/core/skbuff.c (ffffffff819324f2)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81941080)
Location: include/linux/skbuff.h:3274
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
</details>
</li>
</ul>

## Differences
