# Function: <code>pskb_copy</code>

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
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff817764dc)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
Location: include/linux/skbuff.h:2654
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff817e344c)
Location: include/linux/skbuff.h:2654
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:2692
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81813b1d)
Location: include/linux/skbuff.h:2692
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81833d01)
Location: include/linux/skbuff.h:2741
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:2838
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff818b3002)
Location: include/linux/skbuff.h:2838
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:2850
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81908402)
Location: include/linux/skbuff.h:2850
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:2926
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81936695)
Location: include/linux/skbuff.h:2926
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3013
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff8199aa6d)
Location: include/linux/skbuff.h:3013
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff819d1494)
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3101
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81abe57b)
Location: include/linux/skbuff.h:3101
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3127
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81ac9e98)
Location: include/linux/skbuff.h:3127
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81ab4d39)
Location: include/linux/skbuff.h:3191
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3228
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81b71cf4)
Location: include/linux/skbuff.h:3228
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3597
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81d01453)
Location: include/linux/skbuff.h:3597
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3493
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81ec65b3)
Location: include/linux/skbuff.h:3493
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3527
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81f24cf5)
Location: include/linux/skbuff.h:3527
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3552
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81fe94c4)
Location: include/linux/skbuff.h:3552
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
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffff800010c84044)
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (c0d9339c)
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (c000000000d8fc0c)
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffe0007e5964)
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff81971304)
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff8192add4)
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff819dbad4)
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
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
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_realloc_headroom
```
```
In net/ipv4/tcp_output.c (ffffffff819e5754)
Location: include/linux/skbuff.h:3078
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
</details>
</li>
</ul>

## Differences
