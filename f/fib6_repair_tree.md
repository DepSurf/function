# Function: <code>fib6_repair_tree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fib6_node *fib6_repair_tree(struct net *net, struct fib6_node *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff817d9ec0)
Location: net/ipv6/ip6_fib.c:1278
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff817d9ec0-ffffffff817da1e5: fib6_repair_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fib6_node *fib6_repair_tree(struct net *net, struct fib6_node *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff818482f0)
Location: net/ipv6/ip6_fib.c:1280
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff818482f0-ffffffff8184861c: fib6_repair_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fib6_node *fib6_repair_tree(struct net *net, struct fib6_node *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8187a140)
Location: net/ipv6/ip6_fib.c:1286
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff8187a140-ffffffff8187a46c: fib6_repair_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fib6_node *fib6_repair_tree(struct net *net, struct fib6_node *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8189f8d0)
Location: net/ipv6/ip6_fib.c:1324
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff8189f8d0-ffffffff8189fb66: fib6_repair_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81923efb)
Location: net/ipv6/ip6_fib.c:1539
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81922710-ffffffff8192298b: fib6_repair_tree.isra.23.part.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8197c285)
Location: net/ipv6/ip6_fib.c:1598
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff8197aa80-ffffffff8197ad09: fib6_repair_tree.isra.29.part.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b1f65)
Location: net/ipv6/ip6_fib.c:1632
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff819b0750-ffffffff819b09d9: fib6_repair_tree.isra.31.part.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a2044c)
Location: net/ipv6/ip6_fib.c:1704
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81a1eae0-ffffffff81a1ed5d: fib6_repair_tree.isra.0.part.0 (STB_LOCAL)
ffffffff81a20847-ffffffff81a20942: fib6_repair_tree.isra.0.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a5708e)
Location: net/ipv6/ip6_fib.c:1705
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81a55740-ffffffff81a559d9: fib6_repair_tree.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4ed26)
Location: net/ipv6/ip6_fib.c:1772
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81b4d0d0-ffffffff81b4d411: fib6_repair_tree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5d9a6)
Location: net/ipv6/ip6_fib.c:1775
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81b5bd60-ffffffff81b5c099: fib6_repair_tree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4bbff)
Location: net/ipv6/ip6_fib.c:1776
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81b49f20-ffffffff81b4a25b: fib6_repair_tree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c12f1f)
Location: net/ipv6/ip6_fib.c:1777
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81c11280-ffffffff81c115bb: fib6_repair_tree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81dae5ae)
Location: net/ipv6/ip6_fib.c:1778
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81dac6a0-ffffffff81daca2d: fib6_repair_tree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7e0bb)
Location: net/ipv6/ip6_fib.c:1777
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81f7c0b0-ffffffff81f7c43d: fib6_repair_tree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fde2cc)
Location: net/ipv6/ip6_fib.c:1777
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81fdc2d0-ffffffff81fdc65c: fib6_repair_tree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820abe4c)
Location: net/ipv6/ip6_fib.c:1773
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff820a9e30-ffffffff820aa1bc: fib6_repair_tree.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d1bc0c)
Location: net/ipv6/ip6_fib.c:1705
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffff800010d19198-ffff800010d194a0: fib6_repair_tree.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e21070)
Location: net/ipv6/ip6_fib.c:1705
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
c0e1f190-c0e1f548: fib6_repair_tree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e4a534)
Location: net/ipv6/ip6_fib.c:1705
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
c000000000e47720-c000000000e47a88: fib6_repair_tree.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085fbce)
Location: net/ipv6/ip6_fib.c:1705
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffe00085e050-ffffffe00085e284: fib6_repair_tree.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f671e)
Location: net/ipv6/ip6_fib.c:1705
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff819f4dd0-ffffffff819f5069: fib6_repair_tree.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b34de)
Location: net/ipv6/ip6_fib.c:1705
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff819b1b90-ffffffff819b1e29: fib6_repair_tree.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6119e)
Location: net/ipv6/ip6_fib.c:1705
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81a5f850-ffffffff81a5fae9: fib6_repair_tree.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6d65f)
Location: net/ipv6/ip6_fib.c:1705
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81a6bd00-ffffffff81a6bf97: fib6_repair_tree.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
