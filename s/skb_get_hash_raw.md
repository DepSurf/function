# Function: <code>skb_get_hash_raw</code>

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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1072
Inline: True
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1170
Inline: True
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1185
Inline: True
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1178
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1178
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1236
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1236
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1247
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1247
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/skbuff.h:1247
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1285
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1285
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/skbuff.h:1285
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1365
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1365
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/skbuff.h:1365
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/skbuff.h:1362
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
In net/core/dev.c (ffffffff81a0add5)
Location: include/linux/skbuff.h:1368
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
```
```
In net/ipv4/route.c (ffffffff81a94caf)
Location: include/linux/skbuff.h:1368
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv6/route.c (ffffffff81b4756f)
Location: include/linux/skbuff.h:1368
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
In net/core/flow_dissector.c (ffffffff819fa2d1)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_hash
```
```
In net/core/dev.c (ffffffff81a0c025)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
```
```
In net/ipv4/route.c (ffffffff81a9ecaf)
Location: include/linux/skbuff.h:1389
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv6/route.c (ffffffff81b5614f)
Location: include/linux/skbuff.h:1389
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
In net/core/flow_dissector.c (ffffffff819e04b1)
Location: include/linux/skbuff.h:1396
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_hash
```
```
In net/core/dev.c (ffffffff819f21d5)
Location: include/linux/skbuff.h:1396
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
```
```
In net/ipv4/route.c (ffffffff81a89c0d)
Location: include/linux/skbuff.h:1396
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv6/route.c (ffffffff81b43d60)
Location: include/linux/skbuff.h:1396
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
In net/core/flow_dissector.c (ffffffff81a90891)
Location: include/linux/skbuff.h:1409
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_hash
```
```
In net/core/dev.c (ffffffff81aa40a5)
Location: include/linux/skbuff.h:1409
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
```
```
In net/ipv4/route.c (ffffffff81b445d1)
Location: include/linux/skbuff.h:1409
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv6/route.c (ffffffff81c0a8b1)
Location: include/linux/skbuff.h:1409
Inline: True
Inline callers:
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
In net/core/flow_dissector.c (ffffffff81c067f1)
Location: include/linux/skbuff.h:1716
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_hash
```
```
In net/core/gro.c (ffffffff81c540d5)
Location: include/linux/skbuff.h:1716
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/ipv4/route.c (ffffffff81cd1277)
Location: include/linux/skbuff.h:1716
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv6/route.c (ffffffff81da560a)
Location: include/linux/skbuff.h:1716
Inline: True
Inline callers:
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
In net/core/flow_dissector.c (ffffffff81db6191)
Location: include/linux/skbuff.h:1560
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_hash
```
```
In net/core/gro.c (ffffffff81e09805)
Location: include/linux/skbuff.h:1560
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/ipv4/route.c (ffffffff81e917a7)
Location: include/linux/skbuff.h:1560
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv6/route.c (ffffffff81f74b4a)
Location: include/linux/skbuff.h:1560
Inline: True
Inline callers:
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
In net/core/flow_dissector.c (ffffffff81e26721)
Location: include/linux/skbuff.h:1579
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_hash
```
```
In net/core/gro.c (ffffffff81e7bfd5)
Location: include/linux/skbuff.h:1579
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/ipv4/route.c (ffffffff81eeff27)
Location: include/linux/skbuff.h:1579
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv6/route.c (ffffffff81fd4bea)
Location: include/linux/skbuff.h:1579
Inline: True
Inline callers:
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
In net/core/flow_dissector.c (ffffffff81ee46b2)
Location: include/linux/skbuff.h:1586
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_hash
```
```
In net/core/gro.c (ffffffff81f3c325)
Location: include/linux/skbuff.h:1586
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/ipv4/route.c (ffffffff81fb4077)
Location: include/linux/skbuff.h:1586
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv6/route.c (ffffffff820a24fa)
Location: include/linux/skbuff.h:1586
Inline: True
Inline callers:
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/skbuff.h:1362
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
In net/core/dev.c (c0ceec94)
Location: include/linux/skbuff.h:1362
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/route.c (c0d6a1c8)
Location: include/linux/skbuff.h:1362
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv6/route.c (c0e19908)
Location: include/linux/skbuff.h:1362
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/skbuff.h:1362
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/skbuff.h:1362
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/skbuff.h:1362
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/skbuff.h:1362
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/skbuff.h:1362
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
In net/core/dev.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/skbuff.h:1362
Inline: True
```
</details>
</li>
</ul>

## Differences
