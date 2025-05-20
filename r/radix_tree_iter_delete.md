# Function: <code>radix_tree_iter_delete</code>

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
void radix_tree_iter_delete(struct radix_tree_root *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f2ab0)
Location: lib/radix-tree.c:2019
Inline: False
Direct callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_remove
```
**Symbols:**

```
ffffffff818f2ab0-ffffffff818f2acf: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct radix_tree_root *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819778f0)
Location: lib/radix-tree.c:2015
Inline: False
Direct callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_remove
```
**Symbols:**

```
ffffffff819778f0-ffffffff8197790f: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct radix_tree_root *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d4030)
Location: lib/radix-tree.c:2014
Inline: False
Direct callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_remove
```
**Symbols:**

```
ffffffff819d4030-ffffffff819d404f: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d160)
Location: lib/radix-tree.c:1416
Inline: False
```
**Symbols:**

```
ffffffff81a0d160-ffffffff81a0d17f: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7caa0)
Location: lib/radix-tree.c:1403
Inline: False
```
**Symbols:**

```
ffffffff81a7caa0-ffffffff81a7cabf: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab3dd0)
Location: lib/radix-tree.c:1403
Inline: False
```
**Symbols:**

```
ffffffff81ab3dd0-ffffffff81ab3def: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815ee2e0)
Location: lib/radix-tree.c:1395
Inline: False
```
**Symbols:**

```
ffffffff815ee2e0-ffffffff815ee302: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81612a10)
Location: lib/radix-tree.c:1395
Inline: False
```
**Symbols:**

```
ffffffff81612a10-ffffffff81612a32: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f5f90)
Location: lib/radix-tree.c:1396
Inline: False
```
**Symbols:**

```
ffffffff815f5f90-ffffffff815f5fb2: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff816634a0)
Location: lib/radix-tree.c:1396
Inline: False
```
**Symbols:**

```
ffffffff816634a0-ffffffff816634c2: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177d580)
Location: lib/radix-tree.c:1396
Inline: False
```
**Symbols:**

```
ffffffff8177d580-ffffffff8177d5ae: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8203a860)
Location: lib/radix-tree.c:1396
Inline: False
```
**Symbols:**

```
ffffffff8203a860-ffffffff8203a88e: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b8cd0)
Location: lib/radix-tree.c:1394
Inline: False
```
**Symbols:**

```
ffffffff820b8cd0-ffffffff820b8cfe: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff821935e0)
Location: lib/radix-tree.c:1394
Inline: False
```
**Symbols:**

```
ffffffff821935e0-ffffffff8219360e: radix_tree_iter_delete (STB_GLOBAL)
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
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8e118)
Location: lib/radix-tree.c:1403
Inline: False
```
**Symbols:**

```
ffff800010d8e118-ffff800010d8e14c: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e88830)
Location: lib/radix-tree.c:1403
Inline: False
```
**Symbols:**

```
c0e88830-c0e88858: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed0c30)
Location: lib/radix-tree.c:1403
Inline: False
```
**Symbols:**

```
c000000000ed0c30-c000000000ed0c78: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b6d86)
Location: lib/radix-tree.c:1403
Inline: False
```
**Symbols:**

```
ffffffe0008b6d86-ffffffe0008b6dac: radix_tree_iter_delete (STB_GLOBAL)
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
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a52c20)
Location: lib/radix-tree.c:1403
Inline: False
```
**Symbols:**

```
ffffffff81a52c20-ffffffff81a52c3f: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0fd20)
Location: lib/radix-tree.c:1403
Inline: False
```
**Symbols:**

```
ffffffff81a0fd20-ffffffff81a0fd3f: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf010)
Location: lib/radix-tree.c:1403
Inline: False
```
**Symbols:**

```
ffffffff81abf010-ffffffff81abf02f: radix_tree_iter_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void radix_tree_iter_delete(struct xarray *root, struct radix_tree_iter *iter, void **slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acb4e0)
Location: lib/radix-tree.c:1403
Inline: False
```
**Symbols:**

```
ffffffff81acb4e0-ffffffff81acb4ff: radix_tree_iter_delete (STB_GLOBAL)
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
