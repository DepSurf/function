# Function: <code>__find_rr_leaf</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a15af0)
Location: net/ipv6/route.c:787
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff81a15af0-ffffffff81a15d41: __find_rr_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4c730)
Location: net/ipv6/route.c:793
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff81a4c730-ffffffff81a4c981: __find_rr_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b43df0)
Location: net/ipv6/route.c:796
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff81b43df0-ffffffff81b43fe4: __find_rr_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b528a0)
Location: net/ipv6/route.c:779
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff81b528a0-ffffffff81b52a94: __find_rr_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b40230)
Location: net/ipv6/route.c:782
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff81b40230-ffffffff81b40424: __find_rr_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:782
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff81c07750-ffffffff81c0797d: __find_rr_leaf (STB_LOCAL)
ffffffff81d3fd43-ffffffff81d3fd88: __find_rr_leaf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:785
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff81da1c20-ffffffff81da1e6f: __find_rr_leaf (STB_LOCAL)
ffffffff81f0c671-ffffffff81f0c6b6: __find_rr_leaf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:785
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff81f70fa0-ffffffff81f711ef: __find_rr_leaf (STB_LOCAL)
ffffffff820b3cc2-ffffffff820b3d07: __find_rr_leaf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:784
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff81fd1090-ffffffff81fd12df: __find_rr_leaf (STB_LOCAL)
ffffffff82134dd7-ffffffff82134e1c: __find_rr_leaf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:786
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff8209edb0-ffffffff8209efff: __find_rr_leaf (STB_LOCAL)
ffffffff822168eb-ffffffff82216930: __find_rr_leaf.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d13090)
Location: net/ipv6/route.c:793
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffff800010d13090-ffff800010d132c4: __find_rr_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e16c68)
Location: net/ipv6/route.c:793
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
c0e16c68-c0e16ee4: __find_rr_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3cd00)
Location: net/ipv6/route.c:793
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
c000000000e3cd00-c000000000e3d020: __find_rr_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085726c)
Location: net/ipv6/route.c:793
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffe00085726c-ffffffe000857412: __find_rr_leaf (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ebdc0)
Location: net/ipv6/route.c:793
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff819ebdc0-ffffffff819ec011: __find_rr_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a8b80)
Location: net/ipv6/route.c:793
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff819a8b80-ffffffff819a8dd1: __find_rr_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a56840)
Location: net/ipv6/route.c:793
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff81a56840-ffffffff81a56a91: __find_rr_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __find_rr_leaf(struct fib6_info *f6i_start, struct fib6_info *nomatch, u32 metric, struct fib6_result *res, struct fib6_info **cont, int oif, int strict, bool *do_rr, int *mpri);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a628f0)
Location: net/ipv6/route.c:793
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_table_lookup
```
**Symbols:**

```
ffffffff81a628f0-ffffffff81a62b41: __find_rr_leaf (STB_LOCAL)
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
