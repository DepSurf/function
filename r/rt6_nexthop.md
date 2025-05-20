# Function: <code>rt6_nexthop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff817c5185)
Location: include/net/ip6_route.h:199
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81831d75)
Location: include/net/ip6_route.h:219
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81863d19)
Location: include/net/ip6_route.h:224
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff818892d1)
Location: include/net/ip6_route.h:225
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv6/ip6_output.c (ffffffff81909711)
Location: include/net/ip6_route.h:242
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81960a24)
Location: include/net/ip6_route.h:264
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81996d24)
Location: include/net/ip6_route.h:264
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv6/ip6_output.c (ffffffff81a00b24)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a18cc5)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/ipv6/ip6_output.c (ffffffff81a376f4)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a4c2a5)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/ipv6/ip6_output.c (ffffffff81b2d22f)
Location: include/net/ip6_route.h:286
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b42b15)
Location: include/net/ip6_route.h:286
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/core/filter.c (ffffffff81a2eaaa)
Location: include/net/ip6_route.h:286
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b3bc3f)
Location: include/net/ip6_route.h:286
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b51245)
Location: include/net/ip6_route.h:286
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/core/filter.c (ffffffff81a160fe)
Location: include/net/ip6_route.h:294
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81b295b9)
Location: include/net/ip6_route.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b3f165)
Location: include/net/ip6_route.h:294
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/core/filter.c (ffffffff81ac7828)
Location: include/net/ip6_route.h:294
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv6/ip6_output.c (ffffffff81beefd3)
Location: include/net/ip6_route.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81c06c35)
Location: include/net/ip6_route.h:294
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/core/filter.c (ffffffff81c44015)
Location: include/net/ip6_route.h:294
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv6/ip6_output.c (ffffffff81d876a0)
Location: include/net/ip6_route.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81da1495)
Location: include/net/ip6_route.h:294
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/core/filter.c (ffffffff81df8365)
Location: include/net/ip6_route.h:294
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv6/ip6_output.c (ffffffff81f55420)
Location: include/net/ip6_route.h:294
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81f707d5)
Location: include/net/ip6_route.h:294
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/core/filter.c (ffffffff81e699db)
Location: include/net/ip6_route.h:290
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4ea3)
Location: include/net/ip6_route.h:290
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81fd0445)
Location: include/net/ip6_route.h:290
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/core/filter.c (ffffffff81f29048)
Location: include/net/ip6_route.h:293
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv6/ip6_output.c (ffffffff82082578)
Location: include/net/ip6_route.h:293
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff8209dcd5)
Location: include/net/ip6_route.h:293
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/ipv6/ip6_output.c (ffff800010cfa2f0)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffff800010d0ec34)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/ipv6/ip6_output.c (c0dff420)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (c0e167c0)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/ipv6/ip6_output.c (c000000000e1f2bc)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (c000000000e3bc70)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/ipv6/ip6_output.c (ffffffe000843cbe)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffe000856e58)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/ipv6/ip6_output.c (ffffffff819d6d84)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819eb935)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/ipv6/ip6_output.c (ffffffff81993b44)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819a86f5)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/ipv6/ip6_output.c (ffffffff81a41804)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a563b5)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
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
In net/ipv6/ip6_output.c (ffffffff81a4d464)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a62405)
Location: include/net/ip6_route.h:284
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_dst_neigh_lookup
```
</details>
</li>
</ul>

## Differences
