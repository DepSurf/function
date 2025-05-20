# Function: <code>rt6_multipath_rebalance</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81971e59)
Location: net/ipv6/route.c:3917
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81971b80-ffffffff81971cd3: rt6_multipath_rebalance.part.82 (STB_LOCAL)
ffffffff81978790-ffffffff819787b1: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819a75a9)
Location: net/ipv6/route.c:3896
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff819a72d0-ffffffff819a7423: rt6_multipath_rebalance.part.82 (STB_LOCAL)
ffffffff819ae390-ffffffff819ae3b1: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a13be7)
Location: net/ipv6/route.c:4559
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a13900-ffffffff81a13a46: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff81a1c1e0-ffffffff81a1c201: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4a7d7)
Location: net/ipv6/route.c:4572
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a4a4f0-ffffffff81a4a636: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff81a52e60-ffffffff81a52e81: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b44c67)
Location: net/ipv6/route.c:4613
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81b41fd0-ffffffff81b421b6: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff81b4a4c0-ffffffff81b4a4e1: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b53077)
Location: net/ipv6/route.c:4597
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81b50900-ffffffff81b50ae6: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff81b59140-ffffffff81b59161: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b40a07)
Location: net/ipv6/route.c:4612
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81b3ea00-ffffffff81b3ebe6: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff81b47030-ffffffff81b47051: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81c07037)
Location: net/ipv6/route.c:4742
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81c05350-ffffffff81c05536: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff81c0e280-ffffffff81c0e2a1: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81da1bba)
Location: net/ipv6/route.c:4729
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81d9f860-ffffffff81d9fab3: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff81da9350-ffffffff81da9381: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81f70f2a)
Location: net/ipv6/route.c:4729
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81f6e8e0-ffffffff81f6eb33: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff81f78aa0-ffffffff81f78ad1: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd102e)
Location: net/ipv6/route.c:4727
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81fcec10-ffffffff81fcee63: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff81fd8c90-ffffffff81fd8cc1: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff8209e91e)
Location: net/ipv6/route.c:4727
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifup
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff8209c470-ffffffff8209c6c3: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff820a6620-ffffffff820a6651: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffff800010d0d8c0)
Location: net/ipv6/route.c:4572
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffff800010d0d5d0-ffff800010d0d718: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffff800010d16eb0-ffff800010d16ef8: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (c0e140b4)
Location: net/ipv6/route.c:4572
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
c0e13ddc-c0e13f80: rt6_multipath_rebalance.part.0 (STB_LOCAL)
c0e1cacc-c0e1cb00: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (c000000000e39620)
Location: net/ipv6/route.c:4572
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
c000000000e39230-c000000000e393f0: rt6_multipath_rebalance.part.0 (STB_LOCAL)
c000000000e44740-c000000000e4476c: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffe0008555c6)
Location: net/ipv6/route.c:4572
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffe00085539e-ffffffe000855490: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffe00085c112-ffffffe00085c152: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819e9e67)
Location: net/ipv6/route.c:4572
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff819e9b80-ffffffff819e9cc6: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff819f24f0-ffffffff819f2511: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819a6c27)
Location: net/ipv6/route.c:4572
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff819a6940-ffffffff819a6a86: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff819af2b0-ffffffff819af2d1: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a548e7)
Location: net/ipv6/route.c:4572
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a54600-ffffffff81a54746: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff81a5cf70-ffffffff81a5cf91: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rt6_multipath_rebalance(struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a608d7)
Location: net/ipv6/route.c:4572
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
Direct callers:
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/route.c:fib6_ifdown
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a605f0-ffffffff81a60736: rt6_multipath_rebalance.part.0 (STB_LOCAL)
ffffffff81a69350-ffffffff81a69371: rt6_multipath_rebalance (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
