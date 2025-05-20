# Function: <code>rt6_duplicate_nexthop</code>

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
In net/ipv6/route.c (ffffffff8189e48f)
Location: include/net/ip6_route.h:236
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffffffff818a0a32)
Location: include/net/ip6_route.h:236
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/ipv6/route.c (ffffffff81920a71)
Location: include/net/ip6_route.h:253
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffffffff819232ee)
Location: include/net/ip6_route.h:253
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/ipv6/route.c (ffffffff81978ef6)
Location: include/net/ip6_route.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffffffff8197b89c)
Location: include/net/ip6_route.h:275
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/ipv6/route.c (ffffffff819aeb4e)
Location: include/net/ip6_route.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffffffff819b157c)
Location: include/net/ip6_route.h:275
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/ipv6/route.c (ffffffff81a1ccf5)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1f6a9)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffff81a53982)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffffffff81a56307)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffff81b40f18)
Location: include/net/ip6_route.h:297
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4de3c)
Location: include/net/ip6_route.h:297
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffff81b4f9d8)
Location: include/net/ip6_route.h:297
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5ca93)
Location: include/net/ip6_route.h:297
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffff81b47f45)
Location: include/net/ip6_route.h:305
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4ac9f)
Location: include/net/ip6_route.h:305
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffff81c0f1d6)
Location: include/net/ip6_route.h:305
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffffffff81c11fdf)
Location: include/net/ip6_route.h:305
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffff81d9e108)
Location: include/net/ip6_route.h:305
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81dad50a)
Location: include/net/ip6_route.h:305
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffff81f6cf98)
Location: include/net/ip6_route.h:305
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7cf7a)
Location: include/net/ip6_route.h:305
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffff81fcd198)
Location: include/net/ip6_route.h:301
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdd187)
Location: include/net/ip6_route.h:301
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffff8209a9b8)
Location: include/net/ip6_route.h:304
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff820ab2c7)
Location: include/net/ip6_route.h:304
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffff800010d17b70)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffff800010d1ae88)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (c0e1d6f0)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (c0e20264)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (c000000000e456ec)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (c000000000e49330)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffe00085cab6)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffffffe00085f14e)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffff819f3012)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffffffff819f5997)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffff819afdd2)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffffffff819b2757)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffff81a5da92)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffffffff81a60417)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/route.c (ffffffff81a69ea2)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6c8d7)
Location: include/net/ip6_route.h:295
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
</details>
</li>
</ul>

## Differences
