# Function: <code>fib6_nh_release_dsts</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fib6_nh_release_dsts(struct fib6_nh *fib6_nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0d3d0)
Location: net/ipv6/route.c:3683
Inline: False
```
**Symbols:**

```
ffffffff81c0d3d0-ffffffff81c0d460: fib6_nh_release_dsts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fib6_nh_release_dsts(struct fib6_nh *fib6_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81da8380)
Location: net/ipv6/route.c:3659
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_release
Direct callers:
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
ffffffff81d9e020-ffffffff81d9e0b3: fib6_nh_release_dsts.part.0 (STB_LOCAL)
ffffffff81da83c0-ffffffff81da83e4: fib6_nh_release_dsts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fib6_nh_release_dsts(struct fib6_nh *fib6_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81f77a00)
Location: net/ipv6/route.c:3659
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_release
Direct callers:
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
ffffffff81f6d700-ffffffff81f6d79b: fib6_nh_release_dsts.part.0 (STB_LOCAL)
ffffffff81f77a50-ffffffff81f77a74: fib6_nh_release_dsts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fib6_nh_release_dsts(struct fib6_nh *fib6_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd7b80)
Location: net/ipv6/route.c:3657
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_release
Direct callers:
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
ffffffff81fcd820-ffffffff81fcd8bb: fib6_nh_release_dsts.part.0 (STB_LOCAL)
ffffffff81fd7bd0-ffffffff81fd7bf4: fib6_nh_release_dsts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fib6_nh_release_dsts(struct fib6_nh *fib6_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff820a5500)
Location: net/ipv6/route.c:3659
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_release
Direct callers:
  - net/ipv6/route.c:fib6_nh_release
```
**Symbols:**

```
ffffffff8209b070-ffffffff8209b10b: fib6_nh_release_dsts.part.0 (STB_LOCAL)
ffffffff820a5550-ffffffff820a5574: fib6_nh_release_dsts (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
