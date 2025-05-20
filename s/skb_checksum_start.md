# Function: <code>skb_checksum_start</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2213
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f3919)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv6/ip6_checksum.c (ffffffff81871826)
Location: include/linux/skbuff.h:2213
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2230
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81824709)
Location: include/linux/skbuff.h:2230
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5d86)
Location: include/linux/skbuff.h:2230
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2279
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8184541c)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc7e6)
Location: include/linux/skbuff.h:2279
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2366
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c4eac)
Location: include/linux/skbuff.h:2366
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv6/ip6_checksum.c (ffffffff81951596)
Location: include/linux/skbuff.h:2366
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2378
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191ab49)
Location: include/linux/skbuff.h:2378
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2378
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aab2f)
Location: include/linux/skbuff.h:2378
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2456
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81949309)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2456
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e161f)
Location: include/linux/skbuff.h:2456
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2542
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819ad95b)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2542
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a503de)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e460b)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a86ffe)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (ffffffff81ace9ed)
Location: include/linux/skbuff.h:2579
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ad30bb)
Location: include/linux/skbuff.h:2579
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8b98)
Location: include/linux/skbuff.h:2579
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b822ae)
Location: include/linux/skbuff.h:2579
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (ffffffff81adaa0d)
Location: include/linux/skbuff.h:2605
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81adf4fb)
Location: include/linux/skbuff.h:2605
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81ae50b7)
Location: include/linux/skbuff.h:2605
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b9199e)
Location: include/linux/skbuff.h:2605
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (ffffffff81ac5ae8)
Location: include/linux/skbuff.h:2621
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81aca40f)
Location: include/linux/skbuff.h:2621
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81ad036a)
Location: include/linux/skbuff.h:2621
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80bf2)
Location: include/linux/skbuff.h:2621
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (ffffffff81b842fc)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81b88cef)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81b8ed88)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4cc12)
Location: include/linux/skbuff.h:2650
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (ffffffff81d14a1c)
Location: include/linux/skbuff.h:3019
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81d1a053)
Location: include/linux/skbuff.h:3019
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f99a)
Location: include/linux/skbuff.h:3019
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded068)
Location: include/linux/skbuff.h:3019
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (ffffffff81edab5c)
Location: include/linux/skbuff.h:2913
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ee0cc3)
Location: include/linux/skbuff.h:2913
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6b8a)
Location: include/linux/skbuff.h:2913
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc0e68)
Location: include/linux/skbuff.h:2913
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (ffffffff81f39c3a)
Location: include/linux/skbuff.h:2967
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81f405f2)
Location: include/linux/skbuff.h:2967
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81f463dc)
Location: include/linux/skbuff.h:2967
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv6/ip6_checksum.c (ffffffff82021df7)
Location: include/linux/skbuff.h:2967
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (ffffffff81fffd2a)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff82006242)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff8200c51c)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f0f17)
Location: include/linux/skbuff.h:2974
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9905c)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffff800010d5375c)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (c0da3af0)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (c0da6fec)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (c0dadc94)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv6/ip6_checksum.c (c0e54030)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv4/udp.c (c000000000daaa60)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv6/ip6_checksum.c (c000000000e8bf4c)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007f8af8)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b45c)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8198447b)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a2668e)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8193df3b)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e344e)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819eec4b)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9223e)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
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
In net/ipv4/tcp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f8dbb)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/skbuff.h:2556
Inline: True
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e2ee)
Location: include/linux/skbuff.h:2556
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
</details>
</li>
</ul>

## Differences
