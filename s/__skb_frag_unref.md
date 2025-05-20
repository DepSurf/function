# Function: <code>__skb_frag_unref</code>

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
In net/core/skbuff.c (ffffffff81705f57)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_shift
```
```
In net/core/dev.c (ffffffff81715d62)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff817746fe)
Location: include/linux/skbuff.h:2425
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81773dd9)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8177dcf8)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff817e15c6)
Location: include/linux/skbuff.h:2561
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff817a1004)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff817ab668)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81811a96)
Location: include/linux/skbuff.h:2599
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff817be10a)
Location: include/linux/skbuff.h:2648
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff817c9cd8)
Location: include/linux/skbuff.h:2648
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81831e28)
Location: include/linux/skbuff.h:2648
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff818377f3)
Location: include/linux/skbuff.h:2745
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff818435cc)
Location: include/linux/skbuff.h:2745
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff818b0fdd)
Location: include/linux/skbuff.h:2745
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81881cb1)
Location: include/linux/skbuff.h:2757
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8188daa6)
Location: include/linux/skbuff.h:2757
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81906676)
Location: include/linux/skbuff.h:2757
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff818a275f)
Location: include/linux/skbuff.h:2833
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff818ae943)
Location: include/linux/skbuff.h:2833
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81934870)
Location: include/linux/skbuff.h:2833
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff818ed2cb)
Location: include/linux/skbuff.h:2920
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff818fa231)
Location: include/linux/skbuff.h:2920
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff8199853d)
Location: include/linux/skbuff.h:2920
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff8191f3e8)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8192c371)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff819cf141)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff819f2556)
Location: include/linux/skbuff.h:2997
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff819ff881)
Location: include/linux/skbuff.h:2997
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81abc029)
Location: include/linux/skbuff.h:2997
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff819f2556)
Location: include/linux/skbuff.h:3023
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff819ff5e1)
Location: include/linux/skbuff.h:3023
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81ac7769)
Location: include/linux/skbuff.h:3023
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff819d8783)
Location: include/linux/skbuff.h:3087
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff819e5d52)
Location: include/linux/skbuff.h:3087
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81ab2779)
Location: include/linux/skbuff.h:3087
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81a886a3)
Location: include/linux/skbuff.h:3118
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81a97f48)
Location: include/linux/skbuff.h:3118
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f654)
Location: include/linux/skbuff.h:3118
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81bfdda5)
Location: include/linux/skbuff.h:3487
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/gro.c (ffffffff81c53916)
Location: include/linux/skbuff.h:3487
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81cfed17)
Location: include/linux/skbuff.h:3487
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81daa9ea)
Location: include/linux/skbuff.h:3380
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/skbuff.c:skb_shift
```
```
In net/core/gro.c (ffffffff81e090e4)
Location: include/linux/skbuff.h:3380
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3b70)
Location: include/linux/skbuff.h:3380
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
**Symbols:**

```
ffffffff81da55f0-ffffffff81da568e: __skb_frag_unref.isra.0 (STB_LOCAL)
ffffffff81ec3b70-ffffffff81ec3c0e: __skb_frag_unref.isra.0 (STB_LOCAL)
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
In net/core/skbuff.c (ffffffff81e1ea8c)
Location: include/linux/skbuff.h:3446
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/gro.c (ffffffff81e7b74d)
Location: include/linux/skbuff.h:3446
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81f22d32)
Location: include/linux/skbuff.h:3446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81edc0ec)
Location: include/linux/skbuff.h:3471
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/gro.c (ffffffff81f3b9dd)
Location: include/linux/skbuff.h:3471
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81fe7bc2)
Location: include/linux/skbuff.h:3471
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffff800010bb9db8)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffff800010bced00)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffff800010c81f68)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (c0cd67bc)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (c0ce4a78)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (c0d90b34)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (c000000000c92558)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (c000000000ca50a0)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (c000000000d8cd58)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffe000749266)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffe00075519c)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffe0007e3a1c)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff818bf3e8)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff818cc371)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff8196efb1)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81879328)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81886401)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81928aa1)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff819103e8)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8191d371)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff819d9781)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81931548)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8193e891)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff819e33e1)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
</details>
</li>
</ul>

## Differences
