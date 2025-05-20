# Function: <code>flowi6_get_flowlabel</code>

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
In net/core/flow_dissector.c (ffffffff818889da)
Location: include/net/ipv6.h:903
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff81975eb4)
Location: include/net/ipv6.h:903
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff818a95ba)
Location: include/net/ipv6.h:902
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff819abb08)
Location: include/net/ipv6.h:902
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff818f4d01)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff81a19264)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff81926bd1)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff81a4fec4)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff819faad1)
Location: include/net/ipv6.h:964
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff81b4765e)
Location: include/net/ipv6.h:964
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff819fa6e1)
Location: include/net/ipv6.h:964
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff81b5623e)
Location: include/net/ipv6.h:964
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff819e08d1)
Location: include/net/ipv6.h:965
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff81b43e4f)
Location: include/net/ipv6.h:965
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff81a90c41)
Location: include/net/ipv6.h:976
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff81c0ab51)
Location: include/net/ipv6.h:976
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff81c06cd9)
Location: include/net/ipv6.h:1035
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff81da58e5)
Location: include/net/ipv6.h:1035
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff81db6779)
Location: include/net/ipv6.h:1068
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff81f74e25)
Location: include/net/ipv6.h:1068
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff81e271c9)
Location: include/net/ipv6.h:1065
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff81fd4ec2)
Location: include/net/ipv6.h:1065
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff81ee5179)
Location: include/net/ipv6.h:1066
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff820a27d2)
Location: include/net/ipv6.h:1066
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffff800010bc2f24)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffff800010d13e48)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (c0cde274)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (c0e199f4)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (c000000000c9d00c)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (c000000000e4088c)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffe00074fbdc)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffe0008597f8)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff818c6bd1)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff819ef554)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff81880b11)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff819ac314)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff81917bd1)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff81a59fd4)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
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
In net/core/flow_dissector.c (ffffffff81938de1)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
```
```
In net/ipv6/route.c (ffffffff81a66234)
Location: include/net/ipv6.h:960
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
</details>
</li>
</ul>

## Differences
