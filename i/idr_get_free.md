# Function: <code>idr_get_free</code>

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
void **idr_get_free(struct radix_tree_root *root, struct radix_tree_iter *iter, gfp_t gfp, int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f2b20)
Location: lib/radix-tree.c:2141
Inline: False
Direct callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff818f2b20-ffffffff818f2e25: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81972db2)
Location: include/linux/radix-tree.h:362
Inline: True
Inline callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_alloc_cmn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void **idr_get_free(struct radix_tree_root *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d5650)
Location: lib/radix-tree.c:2139
Inline: False
Direct callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff819d5650-ffffffff819d5970: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d8b0)
Location: lib/radix-tree.c:1498
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81a0d8b0-ffffffff81a0db99: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7d220)
Location: lib/radix-tree.c:1485
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81a7d220-ffffffff81a7d4f2: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab4550)
Location: lib/radix-tree.c:1485
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81ab4550-ffffffff81ab482d: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eee90)
Location: lib/radix-tree.c:1477
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff815eee90-ffffffff815ef183: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff816135e0)
Location: lib/radix-tree.c:1477
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff816135e0-ffffffff816138d3: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f6c30)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff815f6c30-ffffffff815f6f21: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81cdf95c-ffffffff81cdfa29: idr_get_free.cold (STB_LOCAL)
ffffffff81664330-ffffffff816646bc: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81ea60f8-ffffffff81ea61ed: idr_get_free.cold (STB_LOCAL)
ffffffff8177e650-ffffffff8177ea0e: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff820b7a75-ffffffff820b7b6a: idr_get_free.cold (STB_LOCAL)
ffffffff8203b2a0-ffffffff8203b65e: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1476
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff82138ee1-ffffffff82138fda: idr_get_free.cold (STB_LOCAL)
ffffffff820b9780-ffffffff820b9b3e: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1476
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff8221ac86-ffffffff8221ad7f: idr_get_free.cold (STB_LOCAL)
ffffffff82194090-ffffffff8219444e: idr_get_free (STB_GLOBAL)
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
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8ea80)
Location: lib/radix-tree.c:1485
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffff800010d8ea80-ffff800010d8ed48: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e891f4)
Location: lib/radix-tree.c:1485
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
c0e891f4-c0e8953c: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed1780)
Location: lib/radix-tree.c:1485
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
c000000000ed1780-c000000000ed1b58: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b7480)
Location: lib/radix-tree.c:1485
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffe0008b7480-ffffffe0008b770a: idr_get_free (STB_GLOBAL)
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
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a533a0)
Location: lib/radix-tree.c:1485
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81a533a0-ffffffff81a5367d: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a104a0)
Location: lib/radix-tree.c:1485
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81a104a0-ffffffff81a1077d: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf790)
Location: lib/radix-tree.c:1485
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81abf790-ffffffff81abfa6d: idr_get_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void **idr_get_free(struct xarray *root, struct radix_tree_iter *iter, gfp_t gfp, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acbc60)
Location: lib/radix-tree.c:1485
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc_u32
```
**Symbols:**

```
ffffffff81acbc60-ffffffff81acbf3d: idr_get_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
