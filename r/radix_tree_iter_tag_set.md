# Function: <code>radix_tree_iter_tag_set</code>

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
void radix_tree_iter_tag_set(struct radix_tree_root *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81452b70)
Location: lib/radix-tree.c:1347
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
**Symbols:**

```
ffffffff81452b70-ffffffff81452bc8: radix_tree_iter_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void radix_tree_iter_tag_set(struct radix_tree_root *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f2a60)
Location: lib/radix-tree.c:1457
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - lib/idr.c:ida_remove
```
**Symbols:**

```
ffffffff818f2a60-ffffffff818f2a7e: radix_tree_iter_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void radix_tree_iter_tag_set(struct radix_tree_root *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81978f00)
Location: lib/radix-tree.c:1455
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - lib/idr.c:ida_remove
```
**Symbols:**

```
ffffffff81978f00-ffffffff81978f1e: radix_tree_iter_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void radix_tree_iter_tag_set(struct radix_tree_root *root, const struct radix_tree_iter *iter, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d55b0)
Location: lib/radix-tree.c:1456
Inline: False
Direct callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - lib/idr.c:ida_remove
```
**Symbols:**

```
ffffffff819d55b0-ffffffff819d55ce: radix_tree_iter_tag_set (STB_GLOBAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
