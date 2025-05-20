# Function: <code>skb_frag_unref</code>

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
In net/core/skbuff.c (ffffffff8170672e)
Location: include/linux/skbuff.h:2437
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff81715d62)
Location: include/linux/skbuff.h:2437
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff817746e8)
Location: include/linux/skbuff.h:2437
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
In net/core/skbuff.c (ffffffff8177118c)
Location: include/linux/skbuff.h:2573
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff8177dce6)
Location: include/linux/skbuff.h:2573
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff817e15b4)
Location: include/linux/skbuff.h:2573
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
In net/core/skbuff.c (ffffffff8179e2ac)
Location: include/linux/skbuff.h:2611
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff817ab656)
Location: include/linux/skbuff.h:2611
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81811a84)
Location: include/linux/skbuff.h:2611
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
In net/core/skbuff.c (ffffffff817bbf52)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff817c9cc6)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81831e13)
Location: include/linux/skbuff.h:2660
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
In net/core/skbuff.c (ffffffff81836118)
Location: include/linux/skbuff.h:2757
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff818435c6)
Location: include/linux/skbuff.h:2757
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff818b0fd6)
Location: include/linux/skbuff.h:2757
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
In net/core/skbuff.c (ffffffff8188036c)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff8188daa6)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81906676)
Location: include/linux/skbuff.h:2769
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
In net/core/skbuff.c (ffffffff818a1246)
Location: include/linux/skbuff.h:2845
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff818ae943)
Location: include/linux/skbuff.h:2845
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81934870)
Location: include/linux/skbuff.h:2845
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
In net/core/skbuff.c (ffffffff818ebb22)
Location: include/linux/skbuff.h:2932
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff818fa231)
Location: include/linux/skbuff.h:2932
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff8199853d)
Location: include/linux/skbuff.h:2932
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
In net/core/skbuff.c (ffffffff8191dc58)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff8192c371)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff819cf141)
Location: include/linux/skbuff.h:2986
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
In net/core/skbuff.c (ffffffff819f09f5)
Location: include/linux/skbuff.h:3009
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff819ff881)
Location: include/linux/skbuff.h:3009
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81abc029)
Location: include/linux/skbuff.h:3009
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
In net/core/skbuff.c (ffffffff819f0865)
Location: include/linux/skbuff.h:3035
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff819ff5e1)
Location: include/linux/skbuff.h:3035
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81ac7769)
Location: include/linux/skbuff.h:3035
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
In net/core/skbuff.c (ffffffff819d5f75)
Location: include/linux/skbuff.h:3099
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff819e5d52)
Location: include/linux/skbuff.h:3099
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81ab2779)
Location: include/linux/skbuff.h:3099
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
In net/core/skbuff.c (ffffffff81a865a3)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff81a97f32)
Location: include/linux/skbuff.h:3136
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f635)
Location: include/linux/skbuff.h:3136
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
In net/core/skbuff.c (ffffffff81bfb82c)
Location: include/linux/skbuff.h:3505
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/gro.c (ffffffff81c53900)
Location: include/linux/skbuff.h:3505
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81cfecf8)
Location: include/linux/skbuff.h:3505
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81daa9cf)
Location: include/linux/skbuff.h:3398
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/gro.c (ffffffff81e090b0)
Location: include/linux/skbuff.h:3398
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3ce0)
Location: include/linux/skbuff.h:3398
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81e1a445)
Location: include/linux/skbuff.h:3458
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/gro.c (ffffffff81e7b703)
Location: include/linux/skbuff.h:3458
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81f22cc2)
Location: include/linux/skbuff.h:3458
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
In net/core/skbuff.c (ffffffff81ed7a05)
Location: include/linux/skbuff.h:3483
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/gro.c (ffffffff81f3b993)
Location: include/linux/skbuff.h:3483
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81fe7b52)
Location: include/linux/skbuff.h:3483
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
In net/core/skbuff.c (ffff800010bb8324)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffff800010bced00)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffff800010c81f68)
Location: include/linux/skbuff.h:2986
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
In net/core/skbuff.c (c0cd4ef0)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (c0ce4a78)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (c0d90b34)
Location: include/linux/skbuff.h:2986
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
In net/core/skbuff.c (c000000000c90320)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (c000000000ca50a0)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (c000000000d8cd58)
Location: include/linux/skbuff.h:2986
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
In net/core/skbuff.c (ffffffe000747b58)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffe00075519c)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffe0007e3a1c)
Location: include/linux/skbuff.h:2986
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
In net/core/skbuff.c (ffffffff818bdc58)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff818cc371)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff8196efb1)
Location: include/linux/skbuff.h:2986
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
In net/core/skbuff.c (ffffffff81877b98)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff81886401)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81928aa1)
Location: include/linux/skbuff.h:2986
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
In net/core/skbuff.c (ffffffff8190ec58)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff8191d371)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff819d9781)
Location: include/linux/skbuff.h:2986
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
In net/core/skbuff.c (ffffffff8192fd88)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/dev.c (ffffffff8193e891)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff819e33e1)
Location: include/linux/skbuff.h:2986
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
</details>
</li>
</ul>

## Differences
