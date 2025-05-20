# Function: <code>radix_tree_iter_tag_clear</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct radix_tree_root *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f2a80)
Location: lib/radix-tree.c:1528
Inline: False
Direct callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff818f2a80-ffffffff818f2a9e: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct radix_tree_root *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81978f20)
Location: lib/radix-tree.c:1526
Inline: False
Direct callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_alloc_cmn
```
**Symbols:**

```
ffffffff81978f20-ffffffff81978f3e: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct radix_tree_root *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d55d0)
Location: lib/radix-tree.c:1527
Inline: False
Direct callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff819d55d0-ffffffff819d55ee: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d890)
Location: lib/radix-tree.c:1081
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81a0d890-ffffffff81a0d8a4: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7d200)
Location: lib/radix-tree.c:1068
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81a7d200-ffffffff81a7d214: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab4530)
Location: lib/radix-tree.c:1068
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81ab4530-ffffffff81ab4544: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eee70)
Location: lib/radix-tree.c:1060
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff815eee70-ffffffff815eee84: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff816135c0)
Location: lib/radix-tree.c:1060
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff816135c0-ffffffff816135d4: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f6c10)
Location: lib/radix-tree.c:1061
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff815f6c10-ffffffff815f6c24: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81664310)
Location: lib/radix-tree.c:1061
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81664310-ffffffff81664324: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177e630)
Location: lib/radix-tree.c:1061
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff8177e630-ffffffff8177e650: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8203b270)
Location: lib/radix-tree.c:1061
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff8203b270-ffffffff8203b290: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b9750)
Location: lib/radix-tree.c:1060
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff820b9750-ffffffff820b9770: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82194060)
Location: lib/radix-tree.c:1060
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff82194060-ffffffff82194080: radix_tree_iter_tag_clear (STB_GLOBAL)
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
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8ea58)
Location: lib/radix-tree.c:1068
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffff800010d8ea58-ffff800010d8ea7c: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e891d4)
Location: lib/radix-tree.c:1068
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
c0e891d4-c0e891f4: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed1760)
Location: lib/radix-tree.c:1068
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
c000000000ed1760-c000000000ed1778: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b7460)
Location: lib/radix-tree.c:1068
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffe0008b7460-ffffffe0008b7480: radix_tree_iter_tag_clear (STB_GLOBAL)
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
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a53380)
Location: lib/radix-tree.c:1068
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81a53380-ffffffff81a53394: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a10480)
Location: lib/radix-tree.c:1068
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81a10480-ffffffff81a10494: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf770)
Location: lib/radix-tree.c:1068
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81abf770-ffffffff81abf784: radix_tree_iter_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void radix_tree_iter_tag_clear(struct xarray *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acbc40)
Location: lib/radix-tree.c:1068
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81acbc40-ffffffff81acbc54: radix_tree_iter_tag_clear (STB_GLOBAL)
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
