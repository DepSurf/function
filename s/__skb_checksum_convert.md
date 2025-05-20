# Function: <code>__skb_checksum_convert</code>

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
In net/ipv4/udp.c (ffffffff8178a5f5)
Location: include/linux/skbuff.h:3249
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff817e4d7c)
Location: include/linux/skbuff.h:3249
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv4/udp.c (ffffffff817f7dd1)
Location: include/linux/skbuff.h:3456
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff81852aaf)
Location: include/linux/skbuff.h:3456
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv4/udp.c (ffffffff81828c99)
Location: include/linux/skbuff.h:3508
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff818847af)
Location: include/linux/skbuff.h:3508
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv4/udp.c (ffffffff81849fec)
Location: include/linux/skbuff.h:3557
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff818aaf80)
Location: include/linux/skbuff.h:3557
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv4/udp.c (ffffffff818c94a3)
Location: include/linux/skbuff.h:3741
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff8192dafd)
Location: include/linux/skbuff.h:3741
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv4/udp.c (ffffffff8191e4d9)
Location: include/linux/skbuff.h:3751
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81984e62)
Location: include/linux/skbuff.h:3751
Inline: True
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
In net/ipv4/udp.c (ffffffff8194d2d6)
Location: include/linux/skbuff.h:3836
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bb5eb)
Location: include/linux/skbuff.h:3836
Inline: True
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
In net/ipv4/udp.c (ffffffff819b1a86)
Location: include/linux/skbuff.h:3945
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a2a1dd)
Location: include/linux/skbuff.h:3945
Inline: True
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
In net/ipv4/udp.c (ffffffff819e8806)
Location: include/linux/skbuff.h:4012
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a60d2d)
Location: include/linux/skbuff.h:4012
Inline: True
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
In net/ipv4/udp.c (ffffffff81ad6ba6)
Location: include/linux/skbuff.h:4046
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81b59c81)
Location: include/linux/skbuff.h:4046
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
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
In net/ipv4/udp.c (ffffffff81ae3186)
Location: include/linux/skbuff.h:4075
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81b682e1)
Location: include/linux/skbuff.h:4075
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
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
In net/ipv4/udp.c (ffffffff81ace089)
Location: include/linux/skbuff.h:4139
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81b565ed)
Location: include/linux/skbuff.h:4139
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
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
In net/ipv4/udp.c (ffffffff81b8ca49)
Location: include/linux/skbuff.h:4176
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81c1cfbd)
Location: include/linux/skbuff.h:4176
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
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
In net/ipv4/udp.c (ffffffff81d1d109)
Location: include/linux/skbuff.h:4595
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81db989a)
Location: include/linux/skbuff.h:4595
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
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
In net/ipv4/udp.c (ffffffff81ee4219)
Location: include/linux/skbuff.h:4491
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81f8991a)
Location: include/linux/skbuff.h:4491
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
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
In net/ipv4/udp.c (ffffffff81f43a8a)
Location: include/linux/skbuff.h:4523
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81fe89eb)
Location: include/linux/skbuff.h:4523
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
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
In net/ipv4/udp.c (ffffffff820099fa)
Location: include/linux/skbuff.h:4563
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff820b754b)
Location: include/linux/skbuff.h:4563
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
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
In net/ipv4/udp.c (ffff800010c9dd00)
Location: include/linux/skbuff.h:4012
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d269b0)
Location: include/linux/skbuff.h:4012
Inline: True
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
In net/ipv4/udp.c (c0dab79c)
Location: include/linux/skbuff.h:4012
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (c0e29ffc)
Location: include/linux/skbuff.h:4012
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
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
In net/ipv4/udp.c (c000000000daf6dc)
Location: include/linux/skbuff.h:4012
Inline: True
```
```
In net/ipv6/udp.c (c000000000e56718)
Location: include/linux/skbuff.h:4012
Inline: True
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
In net/ipv4/udp.c (ffffffe0007fadda)
Location: include/linux/skbuff.h:4012
Inline: True
```
```
In net/ipv6/udp.c (ffffffe000867136)
Location: include/linux/skbuff.h:4012
Inline: True
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
In net/ipv4/udp.c (ffffffff81988676)
Location: include/linux/skbuff.h:4012
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a003bd)
Location: include/linux/skbuff.h:4012
Inline: True
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
In net/ipv4/udp.c (ffffffff81942136)
Location: include/linux/skbuff.h:4012
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bd17d)
Location: include/linux/skbuff.h:4012
Inline: True
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
In net/ipv4/udp.c (ffffffff819f2e46)
Location: include/linux/skbuff.h:4012
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6ae3d)
Location: include/linux/skbuff.h:4012
Inline: True
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
In net/ipv4/udp.c (ffffffff819fd356)
Location: include/linux/skbuff.h:4012
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a7744d)
Location: include/linux/skbuff.h:4012
Inline: True
```
</details>
</li>
</ul>

## Differences
