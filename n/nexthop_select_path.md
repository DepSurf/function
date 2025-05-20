# Function: <code>nexthop_select_path</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d4c00)
Location: net/ipv4/nexthop.c:480
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff819d4c00-ffffffff819d4e79: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0b760)
Location: net/ipv4/nexthop.c:482
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81a0b760-ffffffff81a0b9d9: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afc1e0)
Location: net/ipv4/nexthop.c:545
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81afc1e0-ffffffff81afc44c: nexthop_select_path.part.0.isra.0 (STB_LOCAL)
ffffffff81afc450-ffffffff81afc471: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b09a20)
Location: net/ipv4/nexthop.c:673
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81b09a20-ffffffff81b09c8c: nexthop_select_path.part.0.isra.0 (STB_LOCAL)
ffffffff81b09c90-ffffffff81b09cb1: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af4ad0)
Location: net/ipv4/nexthop.c:1207
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81af4ad0-ffffffff81af4b37: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb537d)
Location: net/ipv4/nexthop.c:1207
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81d3e08d-ffffffff81d3e0dc: nexthop_select_path.cold (STB_LOCAL)
ffffffff81bb5350-ffffffff81bb540a: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d48ead)
Location: net/ipv4/nexthop.c:1208
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81f0a969-ffffffff81f0a9ba: nexthop_select_path.cold (STB_LOCAL)
ffffffff81d48e80-ffffffff81d48f52: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f124ad)
Location: net/ipv4/nexthop.c:1208
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff820b221e-ffffffff820b226f: nexthop_select_path.cold (STB_LOCAL)
ffffffff81f12480-ffffffff81f12552: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f7216d)
Location: net/ipv4/nexthop.c:1208
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff821333ce-ffffffff8213341f: nexthop_select_path.cold (STB_LOCAL)
ffffffff81f72140-ffffffff81f72212: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff8203986d)
Location: net/ipv4/nexthop.c:1231
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff82214def-ffffffff82214e40: nexthop_select_path.cold (STB_LOCAL)
ffffffff82039840-ffffffff82039912: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc4d48)
Location: net/ipv4/nexthop.c:482
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffff800010cc4d48-ffff800010cc4fdc: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dd07d4)
Location: net/ipv4/nexthop.c:482
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
c0dd07d4-c0dd0a80: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000de1020)
Location: net/ipv4/nexthop.c:482
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
c000000000de1020-c000000000de1354: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe00081a0b8)
Location: net/ipv4/nexthop.c:482
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffe00081a0b8-ffffffe00081a31c: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819ab500)
Location: net/ipv4/nexthop.c:482
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff819ab500-ffffffff819ab779: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81964fc0)
Location: net/ipv4/nexthop.c:482
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81964fc0-ffffffff81965239: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a15da0)
Location: net/ipv4/nexthop.c:482
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81a15da0-ffffffff81a16019: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct nexthop *nexthop_select_path(struct nexthop *nh, int hash);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a207e0)
Location: net/ipv4/nexthop.c:482
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv6/route.c:fib6_select_path
```
**Symbols:**

```
ffffffff81a207e0-ffffffff81a20a59: nexthop_select_path (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
