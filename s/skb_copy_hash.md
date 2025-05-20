# Function: <code>skb_copy_hash</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818ebc5f)
Location: include/linux/skbuff.h:1252
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81960f8a)
Location: include/linux/skbuff.h:1252
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff81918f2f)
Location: include/linux/skbuff.h:1290
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff8199583a)
Location: include/linux/skbuff.h:1290
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff8197b065)
Location: include/linux/skbuff.h:1370
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a010f6)
Location: include/linux/skbuff.h:1370
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff819b19d5)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a37cd2)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff81a9c219)
Location: include/linux/skbuff.h:1373
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81b2dca6)
Location: include/linux/skbuff.h:1373
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff81aa6079)
Location: include/linux/skbuff.h:1394
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c6f6)
Location: include/linux/skbuff.h:1394
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff81a91239)
Location: include/linux/skbuff.h:1401
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81b29b56)
Location: include/linux/skbuff.h:1401
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff81b4c5cd)
Location: include/linux/skbuff.h:1414
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81bef70c)
Location: include/linux/skbuff.h:1414
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff81cd9c21)
Location: include/linux/skbuff.h:1721
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81d881f4)
Location: include/linux/skbuff.h:1721
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff81e9a3b1)
Location: include/linux/skbuff.h:1565
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81f55fa4)
Location: include/linux/skbuff.h:1565
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff81ef8d0b)
Location: include/linux/skbuff.h:1584
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5970)
Location: include/linux/skbuff.h:1584
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff81fbcc2b)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff82083040)
Location: include/linux/skbuff.h:1591
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffff800010c623a4)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffff800010cf8450)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (c0d71ba4)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (c0dffba8)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (c000000000d6566c)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (c000000000e2042c)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffe0007c9f48)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffe000844234)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff81951845)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff819d7362)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff8190b335)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81994122)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff819bc015)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a41de2)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/ipv4/ip_output.c (ffffffff819c5925)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a4da72)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
</details>
</li>
</ul>

## Differences
