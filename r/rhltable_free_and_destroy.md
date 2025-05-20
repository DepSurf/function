# Function: <code>rhltable_free_and_destroy</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8186b593)
Location: include/linux/rhashtable.h:1277
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818ebd73)
Location: include/linux/rhashtable.h:1279
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
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
In net/ipv4/ipmr.c (ffffffff81942583)
Location: include/linux/rhashtable.h:1291
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff8199ec43)
Location: include/linux/rhashtable.h:1291
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_free_table
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
In net/ipv4/ipmr.c (ffffffff81972373)
Location: include/linux/rhashtable.h:1159
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff819d55e3)
Location: include/linux/rhashtable.h:1159
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_free_table
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
In net/ipv4/ipmr.c (ffffffff819dbd84)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff81a44504)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_free_table
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
In net/ipv4/ipmr.c (ffffffff81a12cc4)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff81a7b0f4)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_free_table
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
In net/ipv4/ipmr.c (ffffffff81b041a5)
Location: include/linux/rhashtable.h:1262
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (ffffffff81b757f5)
Location: include/linux/rhashtable.h:1262
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv4/ipmr.c (ffffffff81b12315)
Location: include/linux/rhashtable.h:1262
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (ffffffff81b84565)
Location: include/linux/rhashtable.h:1262
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv4/ipmr.c (ffffffff81affa65)
Location: include/linux/rhashtable.h:1262
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (ffffffff81b73205)
Location: include/linux/rhashtable.h:1262
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv4/ipmr.c (ffffffff81bc1865)
Location: include/linux/rhashtable.h:1262
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d7b5)
Location: include/linux/rhashtable.h:1262
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv4/ipmr.c (ffffffff81d56dcd)
Location: include/linux/rhashtable.h:1262
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (ffffffff81ddc13d)
Location: include/linux/rhashtable.h:1262
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv4/ipmr.c (ffffffff81f216bd)
Location: include/linux/rhashtable.h:1273
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (ffffffff81faf35d)
Location: include/linux/rhashtable.h:1273
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv4/ipmr.c (ffffffff81f8094d)
Location: include/linux/rhashtable.h:1273
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (ffffffff8200f12d)
Location: include/linux/rhashtable.h:1273
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv4/ipmr.c (ffffffff82046fcd)
Location: include/linux/rhashtable.h:1273
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (ffffffff820de0bd)
Location: include/linux/rhashtable.h:1273
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
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
In net/ipv4/ipmr.c (ffff800010ccc44c)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffff800010d44fd4)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_free_table
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
In net/ipv4/ipmr.c (c0dd824c)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (c0e47454)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_free_table
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
In net/ipv4/ipmr.c (c000000000deb93c)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (c000000000e79a7c)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_free_table
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
In net/ipv4/ipmr.c (ffffffe000820cbc)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffe00087f8b4)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_free_table
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
In net/ipv4/ipmr.c (ffffffff819b2574)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a784)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_free_table
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
In net/ipv4/ipmr.c (ffffffff8196eba4)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff819d7544)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_free_table
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
In net/ipv4/ipmr.c (ffffffff81a1ce14)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff81a85204)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_free_table
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
In net/ipv4/ipmr.c (ffffffff81a27e44)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff81a91be4)
Location: include/linux/rhashtable.h:1269
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_free_table
```
</details>
</li>
</ul>

## Differences
