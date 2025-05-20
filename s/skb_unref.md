# Function: <code>skb_unref</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bd895)
Location: include/linux/skbuff.h:871
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff817bfe65)
Location: include/linux/skbuff.h:871
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81847038)
Location: include/linux/skbuff.h:871
Inline: True
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
In net/core/skbuff.c (ffffffff81833cb5)
Location: include/linux/skbuff.h:951
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff81839a16)
Location: include/linux/skbuff.h:951
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c6a98)
Location: include/linux/skbuff.h:951
Inline: True
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
In net/core/skbuff.c (ffffffff8187da15)
Location: include/linux/skbuff.h:955
Inline: True
```
```
In net/core/datagram.c (ffffffff81884155)
Location: include/linux/skbuff.h:955
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191c4cd)
Location: include/linux/skbuff.h:955
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
In net/core/skbuff.c (ffffffff8189e5e5)
Location: include/linux/skbuff.h:979
Inline: True
```
```
In net/core/datagram.c (ffffffff818a45d5)
Location: include/linux/skbuff.h:979
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194aa9d)
Location: include/linux/skbuff.h:979
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
In net/core/skbuff.c (ffffffff818e9545)
Location: include/linux/skbuff.h:1012
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff818efd55)
Location: include/linux/skbuff.h:1012
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819af0dc)
Location: include/linux/skbuff.h:1012
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
In net/core/skbuff.c (ffffffff8191b6a5)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff81921d75)
Location: include/linux/skbuff.h:1008
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e5dec)
Location: include/linux/skbuff.h:1008
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
In net/core/skbuff.c (ffffffff819ed545)
Location: include/linux/skbuff.h:1040
Inline: True
```
```
In net/core/datagram.c (ffffffff819f4ee5)
Location: include/linux/skbuff.h:1040
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad383c)
Location: include/linux/skbuff.h:1040
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
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
In net/core/skbuff.c (ffffffff819ed215)
Location: include/linux/skbuff.h:1047
Inline: True
```
```
In net/core/datagram.c (ffffffff819f4905)
Location: include/linux/skbuff.h:1047
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81adebfc)
Location: include/linux/skbuff.h:1047
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
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
In net/core/skbuff.c (ffffffff819d35e5)
Location: include/linux/skbuff.h:1053
Inline: True
```
```
In net/core/datagram.c (ffffffff819da9e0)
Location: include/linux/skbuff.h:1053
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ac9bec)
Location: include/linux/skbuff.h:1053
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
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
In net/core/skbuff.c (ffffffff81a83345)
Location: include/linux/skbuff.h:1065
Inline: True
```
```
In net/core/datagram.c (ffffffff81a8b060)
Location: include/linux/skbuff.h:1065
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8847c)
Location: include/linux/skbuff.h:1065
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
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
In net/core/skbuff.c (ffffffff81bf81a5)
Location: include/linux/skbuff.h:1355
Inline: True
```
```
In net/core/datagram.c (ffffffff81c007d0)
Location: include/linux/skbuff.h:1355
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1bbdb)
Location: include/linux/skbuff.h:1355
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
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
In net/core/skbuff.c (ffffffff81da6f65)
Location: include/linux/skbuff.h:1197
Inline: True
Inline callers:
  - net/core/skbuff.c:kfree_skb_reason
```
```
In net/core/datagram.c (ffffffff81dafb00)
Location: include/linux/skbuff.h:1197
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee2abb)
Location: include/linux/skbuff.h:1197
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
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
In net/core/skbuff.c (ffffffff81e1625f)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
```
```
In net/core/datagram.c (ffffffff81e1fd70)
Location: include/linux/skbuff.h:1216
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f3f7db)
Location: include/linux/skbuff.h:1216
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
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
In net/core/skbuff.c (ffffffff81ed367f)
Location: include/linux/skbuff.h:1223
Inline: True
Inline callers:
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
```
```
In net/core/datagram.c (ffffffff81edd420)
Location: include/linux/skbuff.h:1223
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82007e7f)
Location: include/linux/skbuff.h:1223
Inline: True
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
In net/core/skbuff.c (ffff800010bb5bb0)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffff800010bbc438)
Location: include/linux/skbuff.h:1008
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c99578)
Location: include/linux/skbuff.h:1008
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
In net/core/skbuff.c (c0cd2ba8)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (c0cd8974)
Location: include/linux/skbuff.h:1008
Inline: True
```
```
In net/ipv4/udp.c (c0da82c0)
Location: include/linux/skbuff.h:1008
Inline: True
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
In net/core/skbuff.c (c000000000c8cfd8)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (c000000000c947d0)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/ipv4/udp.c (c000000000dab1b8)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
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
In net/core/skbuff.c (ffffffe000745ab8)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffe00074b140)
Location: include/linux/skbuff.h:1008
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007f7172)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/ipv4/udp.c:skb_consume_udp
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
In net/core/skbuff.c (ffffffff818bb6a5)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff818c1d75)
Location: include/linux/skbuff.h:1008
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81985c5c)
Location: include/linux/skbuff.h:1008
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
In net/core/skbuff.c (ffffffff818755e5)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff8187bcb5)
Location: include/linux/skbuff.h:1008
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8193f71c)
Location: include/linux/skbuff.h:1008
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
In net/core/skbuff.c (ffffffff8190c6a5)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff81912d75)
Location: include/linux/skbuff.h:1008
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f042c)
Location: include/linux/skbuff.h:1008
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
In net/core/skbuff.c (ffffffff8192d7d5)
Location: include/linux/skbuff.h:1008
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff81933ef5)
Location: include/linux/skbuff.h:1008
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fadac)
Location: include/linux/skbuff.h:1008
Inline: True
```
</details>
</li>
</ul>

## Differences
