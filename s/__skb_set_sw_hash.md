# Function: <code>__skb_set_sw_hash</code>

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
In net/core/flow_dissector.c (ffffffff817119bf)
Location: include/linux/skbuff.h:979
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff817c509d)
Location: include/linux/skbuff.h:979
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
In net/core/flow_dissector.c (ffffffff817793cc)
Location: include/linux/skbuff.h:1076
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff8183533b)
Location: include/linux/skbuff.h:1076
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
In net/core/flow_dissector.c (ffffffff817a6534)
Location: include/linux/skbuff.h:1091
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81866e62)
Location: include/linux/skbuff.h:1091
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
In net/core/flow_dissector.c (ffffffff817c4724)
Location: include/linux/skbuff.h:1084
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff817e7b76)
Location: include/linux/skbuff.h:1084
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff8188b60c)
Location: include/linux/skbuff.h:1084
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
In net/core/flow_dissector.c (ffffffff8183f94e)
Location: include/linux/skbuff.h:1158
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81862ab6)
Location: include/linux/skbuff.h:1158
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff8190c885)
Location: include/linux/skbuff.h:1158
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
Location: include/linux/skbuff.h:1163
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff818ae7f5)
Location: include/linux/skbuff.h:1163
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81963cca)
Location: include/linux/skbuff.h:1163
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
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff818d2a95)
Location: include/linux/skbuff.h:1183
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81998c65)
Location: include/linux/skbuff.h:1183
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
Location: include/linux/skbuff.h:1235
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff8191fd95)
Location: include/linux/skbuff.h:1235
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81a04abe)
Location: include/linux/skbuff.h:1235
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
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81951fd5)
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b6af)
Location: include/linux/skbuff.h:1231
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
Location: include/linux/skbuff.h:1263
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81a231d5)
Location: include/linux/skbuff.h:1263
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81b30c7b)
Location: include/linux/skbuff.h:1263
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
Location: include/linux/skbuff.h:1280
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81a23595)
Location: include/linux/skbuff.h:1280
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f8a8)
Location: include/linux/skbuff.h:1280
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
Location: include/linux/skbuff.h:1288
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81a0a8c5)
Location: include/linux/skbuff.h:1288
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d759)
Location: include/linux/skbuff.h:1288
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
Location: include/linux/skbuff.h:1301
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81abcd45)
Location: include/linux/skbuff.h:1301
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3977)
Location: include/linux/skbuff.h:1301
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
Location: include/linux/skbuff.h:1608
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81c37855)
Location: include/linux/skbuff.h:1608
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c54f)
Location: include/linux/skbuff.h:1608
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
Location: include/linux/skbuff.h:1452
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81deb0f5)
Location: include/linux/skbuff.h:1452
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a50f)
Location: include/linux/skbuff.h:1452
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
Location: include/linux/skbuff.h:1471
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81e5c8f5)
Location: include/linux/skbuff.h:1471
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81fba215)
Location: include/linux/skbuff.h:1471
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
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81f1bce5)
Location: include/linux/skbuff.h:1478
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff82087665)
Location: include/linux/skbuff.h:1478
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
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffff800010bf414c)
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffff800010cfc824)
Location: include/linux/skbuff.h:1231
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
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (c0d0c940)
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (c0e03cb0)
Location: include/linux/skbuff.h:1231
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
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (c000000000cd92a8)
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (c000000000e2442c)
Location: include/linux/skbuff.h:1231
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
In net/core/flow_dissector.c (ffffffe0007516ae)
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffe00077563c)
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffe00084707a)
Location: include/linux/skbuff.h:1231
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
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff818f1fa5)
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff819dad3f)
Location: include/linux/skbuff.h:1231
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
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff818abdd5)
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81997aff)
Location: include/linux/skbuff.h:1231
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
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff81942fd5)
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81a457bf)
Location: include/linux/skbuff.h:1231
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
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_hash
```
```
In net/core/filter.c (ffffffff819648c5)
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_set_hash
```
```
In net/ipv6/ip6_output.c (ffffffff81a5148f)
Location: include/linux/skbuff.h:1231
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
</details>
</li>
</ul>

## Differences
