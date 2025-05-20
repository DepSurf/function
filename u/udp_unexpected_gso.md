# Function: <code>udp_unexpected_gso</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194d0e5)
Location: include/linux/udp.h:136
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bb3d5)
Location: include/linux/udp.h:136
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
In net/ipv4/udp.c (ffffffff819b18b5)
Location: include/linux/udp.h:132
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a29fe5)
Location: include/linux/udp.h:132
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
In net/ipv4/udp.c (ffffffff819e8615)
Location: include/linux/udp.h:132
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a60b05)
Location: include/linux/udp.h:132
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
In net/ipv4/udp.c (ffffffff81ad6b19)
Location: include/linux/udp.h:132
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81b59be3)
Location: include/linux/udp.h:132
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
In net/ipv4/udp.c (ffffffff81ae30f9)
Location: include/linux/udp.h:132
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81b68243)
Location: include/linux/udp.h:132
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
In net/ipv4/udp.c (ffffffff81acdc75)
Location: include/linux/udp.h:134
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b56525)
Location: include/linux/udp.h:134
Inline: True
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
In net/ipv4/udp.c (ffffffff81b8c635)
Location: include/linux/udp.h:134
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1cb95)
Location: include/linux/udp.h:134
Inline: True
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
In net/ipv4/udp.c (ffffffff81d1cca5)
Location: include/linux/udp.h:129
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81db9455)
Location: include/linux/udp.h:129
Inline: True
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
In net/ipv4/udp.c (ffffffff81ee3d95)
Location: include/linux/udp.h:136
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81f894b5)
Location: include/linux/udp.h:136
Inline: True
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
In net/ipv4/udp.c (ffffffff81f43605)
Location: include/linux/udp.h:133
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81fe88f5)
Location: include/linux/udp.h:133
Inline: True
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
In net/ipv4/udp.c (ffffffff82009565)
Location: include/linux/udp.h:143
Inline: True
```
```
In net/ipv6/udp.c (ffffffff820b7445)
Location: include/linux/udp.h:143
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
In net/ipv4/udp.c (ffff800010c9dab8)
Location: include/linux/udp.h:132
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d26758)
Location: include/linux/udp.h:132
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
In net/ipv4/udp.c (c0dab56c)
Location: include/linux/udp.h:132
Inline: True
```
```
In net/ipv6/udp.c (c0e29dac)
Location: include/linux/udp.h:132
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
In net/ipv4/udp.c (c000000000daf40c)
Location: include/linux/udp.h:132
Inline: True
```
```
In net/ipv6/udp.c (c000000000e5643c)
Location: include/linux/udp.h:132
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
In net/ipv4/udp.c (ffffffe0007fabe4)
Location: include/linux/udp.h:132
Inline: True
```
```
In net/ipv6/udp.c (ffffffe000866f40)
Location: include/linux/udp.h:132
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
In net/ipv4/udp.c (ffffffff81988485)
Location: include/linux/udp.h:132
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a00195)
Location: include/linux/udp.h:132
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
In net/ipv4/udp.c (ffffffff81941f45)
Location: include/linux/udp.h:132
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bcf55)
Location: include/linux/udp.h:132
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
In net/ipv4/udp.c (ffffffff819f2c55)
Location: include/linux/udp.h:132
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6ac15)
Location: include/linux/udp.h:132
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
In net/ipv4/udp.c (ffffffff819fd165)
Location: include/linux/udp.h:132
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a77225)
Location: include/linux/udp.h:132
Inline: True
```
</details>
</li>
</ul>

## Differences
