# Function: <code>radix_tree_extend</code>

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
In lib/radix-tree.c (ffffffff813eed21)
Location: lib/radix-tree.c:326
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_create
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
In lib/radix-tree.c (ffffffff81435464)
Location: lib/radix-tree.c:492
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_create
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
In lib/radix-tree.c (ffffffff81451ac6)
Location: lib/radix-tree.c:533
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int radix_tree_extend(struct radix_tree_root *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f16c0)
Location: lib/radix-tree.c:619
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:__radix_tree_create
```
**Symbols:**

```
ffffffff818f16c0-ffffffff818f1824: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int radix_tree_extend(struct radix_tree_root *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81977b70)
Location: lib/radix-tree.c:619
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free_cmn
  - lib/radix-tree.c:__radix_tree_create
```
**Symbols:**

```
ffffffff81977b70-ffffffff81977cd4: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int radix_tree_extend(struct radix_tree_root *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d4200)
Location: lib/radix-tree.c:620
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:__radix_tree_create
```
**Symbols:**

```
ffffffff819d4200-ffffffff819d4365: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d270)
Location: lib/radix-tree.c:430
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff81a0d270-ffffffff81a0d3e5: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7cba0)
Location: lib/radix-tree.c:417
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff81a7cba0-ffffffff81a7cd12: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab3ed0)
Location: lib/radix-tree.c:417
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff81ab3ed0-ffffffff81ab4042: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eded0)
Location: lib/radix-tree.c:409
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:__radix_tree_create
```
**Symbols:**

```
ffffffff815eded0-ffffffff815ee040: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81612600)
Location: lib/radix-tree.c:409
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:__radix_tree_create
```
**Symbols:**

```
ffffffff81612600-ffffffff81612770: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f5ce0)
Location: lib/radix-tree.c:409
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff815f5ce0-ffffffff815f5e50: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:409
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff816631b0-ffffffff8166331a: radix_tree_extend (STB_LOCAL)
ffffffff81cdf50b-ffffffff81cdf523: radix_tree_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:409
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff8177d1f0-ffffffff8177d382: radix_tree_extend (STB_LOCAL)
ffffffff81ea5cc5-ffffffff81ea5ce3: radix_tree_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:409
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff82039aa0-ffffffff82039c27: radix_tree_extend (STB_LOCAL)
ffffffff820b7634-ffffffff820b7652: radix_tree_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:408
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff820b7dc0-ffffffff820b7f43: radix_tree_extend (STB_LOCAL)
ffffffff82138b3b-ffffffff82138b53: radix_tree_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:408
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff821926d0-ffffffff82192853: radix_tree_extend (STB_LOCAL)
ffffffff8221a8e0-ffffffff8221a8f8: radix_tree_extend.cold (STB_LOCAL)
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
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8e238)
Location: lib/radix-tree.c:417
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffff800010d8e238-ffff800010d8e3e4: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e88a7c)
Location: lib/radix-tree.c:417
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
c0e88a7c-c0e88c00: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed0db0)
Location: lib/radix-tree.c:417
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
c000000000ed0db0-c000000000ed1024: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b6e72)
Location: lib/radix-tree.c:417
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffe0008b6e72-ffffffe0008b6ff2: radix_tree_extend (STB_LOCAL)
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
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a52d20)
Location: lib/radix-tree.c:417
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff81a52d20-ffffffff81a52e92: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0fe20)
Location: lib/radix-tree.c:417
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff81a0fe20-ffffffff81a0ff92: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf110)
Location: lib/radix-tree.c:417
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff81abf110-ffffffff81abf282: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int radix_tree_extend(struct xarray *root, gfp_t gfp, long unsigned int index, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acb5e0)
Location: lib/radix-tree.c:417
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff81acb5e0-ffffffff81acb752: radix_tree_extend (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root *root</code> ➡️ <code>struct xarray *root</code>
</li>
</ul>
</details>
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
