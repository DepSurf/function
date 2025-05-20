# Function: <code>flow_keys_have_l4</code>

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
In net/core/flow_dissector.c (ffffffff817119a1)
Location: include/net/flow_dissector.h:180
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff817c5077)
Location: include/net/flow_dissector.h:180
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:__ip6_make_skb
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
In net/core/flow_dissector.c (ffffffff817793bc)
Location: include/net/flow_dissector.h:180
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81835319)
Location: include/net/flow_dissector.h:180
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff817a6524)
Location: include/net/flow_dissector.h:208
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81866e5a)
Location: include/net/flow_dissector.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff817c4714)
Location: include/net/flow_dissector.h:255
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff8188b606)
Location: include/net/flow_dissector.h:255
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff8183f948)
Location: include/net/flow_dissector.h:264
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff8190c87f)
Location: include/net/flow_dissector.h:264
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff8188a205)
Location: include/net/flow_dissector.h:269
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81963cca)
Location: include/net/flow_dissector.h:269
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff818ab11d)
Location: include/net/flow_dissector.h:288
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81998c65)
Location: include/net/flow_dissector.h:288
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff818f6a6b)
Location: include/net/flow_dissector.h:312
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81a04abe)
Location: include/net/flow_dissector.h:312
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff81928936)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b6af)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff819fc9d7)
Location: include/net/flow_dissector.h:336
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81b30c7b)
Location: include/net/flow_dissector.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff819fc621)
Location: include/net/flow_dissector.h:345
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f8a8)
Location: include/net/flow_dissector.h:345
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff819e2ea1)
Location: include/net/flow_dissector.h:345
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d759)
Location: include/net/flow_dissector.h:345
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff81a93483)
Location: include/net/flow_dissector.h:345
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3977)
Location: include/net/flow_dissector.h:345
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff81c09623)
Location: include/net/flow_dissector.h:357
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c54f)
Location: include/net/flow_dissector.h:357
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff81db93a3)
Location: include/net/flow_dissector.h:395
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a50f)
Location: include/net/flow_dissector.h:395
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff81e299f3)
Location: include/net/flow_dissector.h:420
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81fba215)
Location: include/net/flow_dissector.h:420
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff81ee7a63)
Location: include/net/flow_dissector.h:430
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff82087665)
Location: include/net/flow_dissector.h:430
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffff800010bc4bec)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffff800010cfc824)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (c0ce01cc)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (c0e03cb0)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (c000000000c9f324)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (c000000000e2442c)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffe0007516a6)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffe000847072)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff818c8936)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff819dad3f)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff81882876)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81997aff)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff81919936)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81a457bf)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
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
In net/core/flow_dissector.c (ffffffff8193ab76)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81a5148f)
Location: include/net/flow_dissector.h:315
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
</details>
</li>
</ul>

## Differences
