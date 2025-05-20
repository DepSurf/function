# Function: <code>__skb_checksum_convert_check</code>

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
In net/ipv4/udp.c (0)
Location: include/linux/skbuff.h:3243
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/skbuff.h:3243
Inline: True
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
In net/ipv4/udp.c (ffffffff817f77ec)
Location: include/linux/skbuff.h:3450
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff81852a67)
Location: include/linux/skbuff.h:3450
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
In net/ipv4/udp.c (ffffffff818286f0)
Location: include/linux/skbuff.h:3502
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff81884767)
Location: include/linux/skbuff.h:3502
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
In net/ipv4/udp.c (ffffffff818499ab)
Location: include/linux/skbuff.h:3552
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff818aaf38)
Location: include/linux/skbuff.h:3552
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
In net/ipv4/udp.c (ffffffff818c9468)
Location: include/linux/skbuff.h:3736
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/udp.c (ffffffff8192dab5)
Location: include/linux/skbuff.h:3736
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
In net/ipv4/udp.c (ffffffff8191e4a1)
Location: include/linux/skbuff.h:3746
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81984e0a)
Location: include/linux/skbuff.h:3746
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
In net/ipv4/udp.c (ffffffff8194d2a1)
Location: include/linux/skbuff.h:3831
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bb59a)
Location: include/linux/skbuff.h:3831
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
In net/ipv4/udp.c (ffffffff819b1a51)
Location: include/linux/skbuff.h:3940
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a2a18b)
Location: include/linux/skbuff.h:3940
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
In net/ipv4/udp.c (ffffffff819e87d1)
Location: include/linux/skbuff.h:4007
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a60cdb)
Location: include/linux/skbuff.h:4007
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
In net/ipv4/udp.c (ffffffff81ad6b71)
Location: include/linux/skbuff.h:4041
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81b59c4a)
Location: include/linux/skbuff.h:4041
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
In net/ipv4/udp.c (ffffffff81ae3151)
Location: include/linux/skbuff.h:4070
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81b682aa)
Location: include/linux/skbuff.h:4070
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
In net/ipv4/udp.c (ffffffff81ace054)
Location: include/linux/skbuff.h:4134
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81b5659e)
Location: include/linux/skbuff.h:4134
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
In net/ipv4/udp.c (ffffffff81b8ca14)
Location: include/linux/skbuff.h:4171
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81c1cf6e)
Location: include/linux/skbuff.h:4171
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
In net/ipv4/udp.c (ffffffff81d1d0d4)
Location: include/linux/skbuff.h:4590
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81db983d)
Location: include/linux/skbuff.h:4590
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
In net/ipv4/udp.c (ffffffff81ee41e4)
Location: include/linux/skbuff.h:4486
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81f898bd)
Location: include/linux/skbuff.h:4486
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
In net/ipv4/udp.c (ffffffff81f43a54)
Location: include/linux/skbuff.h:4518
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81fe898d)
Location: include/linux/skbuff.h:4518
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
In net/ipv4/udp.c (ffffffff820099c4)
Location: include/linux/skbuff.h:4558
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff820b74ed)
Location: include/linux/skbuff.h:4558
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
In net/ipv4/udp.c (ffff800010c9dca8)
Location: include/linux/skbuff.h:4007
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d26950)
Location: include/linux/skbuff.h:4007
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
In net/ipv4/udp.c (c0dab74c)
Location: include/linux/skbuff.h:4007
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (c0e29f98)
Location: include/linux/skbuff.h:4007
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
In net/ipv4/udp.c (c000000000daf68c)
Location: include/linux/skbuff.h:4007
Inline: True
```
```
In net/ipv6/udp.c (c000000000e566a0)
Location: include/linux/skbuff.h:4007
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
In net/ipv4/udp.c (ffffffe0007fadac)
Location: include/linux/skbuff.h:4007
Inline: True
```
```
In net/ipv6/udp.c (ffffffe0008670e2)
Location: include/linux/skbuff.h:4007
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
In net/ipv4/udp.c (ffffffff81988641)
Location: include/linux/skbuff.h:4007
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a0036b)
Location: include/linux/skbuff.h:4007
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
In net/ipv4/udp.c (ffffffff81942101)
Location: include/linux/skbuff.h:4007
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bd12b)
Location: include/linux/skbuff.h:4007
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
In net/ipv4/udp.c (ffffffff819f2e11)
Location: include/linux/skbuff.h:4007
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6adeb)
Location: include/linux/skbuff.h:4007
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
In net/ipv4/udp.c (ffffffff819fd321)
Location: include/linux/skbuff.h:4007
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a773fb)
Location: include/linux/skbuff.h:4007
Inline: True
```
</details>
</li>
</ul>

## Differences
