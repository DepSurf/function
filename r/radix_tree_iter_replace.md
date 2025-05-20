# Function: <code>radix_tree_iter_replace</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct radix_tree_root *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff814521a0)
Location: lib/radix-tree.c:1115
Inline: False
```
**Symbols:**

```
ffffffff814521a0-ffffffff814521b5: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct radix_tree_root *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f2050)
Location: lib/radix-tree.c:1241
Inline: False
Direct callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff818f2050-ffffffff818f2065: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct radix_tree_root *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819784f0)
Location: lib/radix-tree.c:1239
Inline: False
Direct callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_alloc_cmn
```
**Symbols:**

```
ffffffff819784f0-ffffffff81978502: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct radix_tree_root *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d4c10)
Location: lib/radix-tree.c:1240
Inline: False
Direct callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff819d4c10-ffffffff819d4c22: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d880)
Location: lib/radix-tree.c:952
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81a0d880-ffffffff81a0d88f: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7d1f0)
Location: lib/radix-tree.c:939
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81a7d1f0-ffffffff81a7d1ff: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab4520)
Location: lib/radix-tree.c:939
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81ab4520-ffffffff81ab452f: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eee60)
Location: lib/radix-tree.c:931
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff815eee60-ffffffff815eee6f: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff816135b0)
Location: lib/radix-tree.c:931
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff816135b0-ffffffff816135bf: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f6c00)
Location: lib/radix-tree.c:932
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff815f6c00-ffffffff815f6c0f: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81664300)
Location: lib/radix-tree.c:932
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81664300-ffffffff8166430f: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177e610)
Location: lib/radix-tree.c:932
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff8177e610-ffffffff8177e62b: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8203b240)
Location: lib/radix-tree.c:932
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff8203b240-ffffffff8203b25b: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b9720)
Location: lib/radix-tree.c:931
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff820b9720-ffffffff820b973b: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82194030)
Location: lib/radix-tree.c:931
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff82194030-ffffffff8219404b: radix_tree_iter_replace (STB_GLOBAL)
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
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8ea40)
Location: lib/radix-tree.c:939
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffff800010d8ea40-ffff800010d8ea58: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e891bc)
Location: lib/radix-tree.c:939
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
c0e891bc-c0e891d4: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed1750)
Location: lib/radix-tree.c:939
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
c000000000ed1750-c000000000ed1760: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b7446)
Location: lib/radix-tree.c:939
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffe0008b7446-ffffffe0008b7460: radix_tree_iter_replace (STB_GLOBAL)
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
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a53370)
Location: lib/radix-tree.c:939
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81a53370-ffffffff81a5337f: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a10470)
Location: lib/radix-tree.c:939
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81a10470-ffffffff81a1047f: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf760)
Location: lib/radix-tree.c:939
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81abf760-ffffffff81abf76f: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void radix_tree_iter_replace(struct xarray *root, const struct radix_tree_iter *iter, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acbc30)
Location: lib/radix-tree.c:939
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81acbc30-ffffffff81acbc3f: radix_tree_iter_replace (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
