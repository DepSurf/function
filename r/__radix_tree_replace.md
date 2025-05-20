# Function: <code>__radix_tree_replace</code>

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
void __radix_tree_replace(struct radix_tree_root *root, struct radix_tree_node *node, void **slot, void *item, radix_tree_update_node_t update_node, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81451f70)
Location: lib/radix-tree.c:1060
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:page_cache_tree_insert
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_radix_tree_replace
  - fs/dax.c:dax_insert_mapping_entry
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_replace
```
**Symbols:**

```
ffffffff81451f70-ffffffff81452097: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __radix_tree_replace(struct radix_tree_root *root, struct radix_tree_node *node, void **slot, void *item, radix_tree_update_node_t update_node, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f1f40)
Location: lib/radix-tree.c:1181
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:page_cache_tree_insert
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_radix_tree_replace
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
ffffffff818f1f40-ffffffff818f202a: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __radix_tree_replace(struct radix_tree_root *root, struct radix_tree_node *node, void **slot, void *item, radix_tree_update_node_t update_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819783f0)
Location: lib/radix-tree.c:1179
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:page_cache_tree_insert
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_radix_tree_replace
  - fs/dax.c:dax_insert_mapping_entry
  - lib/idr.c:idr_replace_ext
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
ffffffff819783f0-ffffffff819784cb: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __radix_tree_replace(struct radix_tree_root *root, struct radix_tree_node *node, void **slot, void *item, radix_tree_update_node_t update_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d4b10)
Location: lib/radix-tree.c:1180
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:page_cache_tree_insert
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_radix_tree_replace
  - fs/dax.c:dax_insert_mapping_entry
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
ffffffff819d4b10-ffffffff819d4be4: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d770)
Location: lib/radix-tree.c:897
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
ffffffff81a0d770-ffffffff81a0d852: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7d0b0)
Location: lib/radix-tree.c:884
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
ffffffff81a7d0b0-ffffffff81a7d1c8: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab43e0)
Location: lib/radix-tree.c:884
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
ffffffff81ab43e0-ffffffff81ab44f8: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eeb40)
Location: lib/radix-tree.c:876
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_replace_slot
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
```
**Symbols:**

```
ffffffff815eed80-ffffffff815eee51: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81613290)
Location: lib/radix-tree.c:876
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_replace_slot
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
```
**Symbols:**

```
ffffffff816134d0-ffffffff816135a1: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f68f0)
Location: lib/radix-tree.c:876
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_replace_slot
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
```
**Symbols:**

```
ffffffff815f6b30-ffffffff815f6bfa: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81663b50)
Location: lib/radix-tree.c:876
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_replace_slot
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
```
**Symbols:**

```
ffffffff81664230-ffffffff816642fa: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177dd30)
Location: lib/radix-tree.c:876
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_replace_slot
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
```
**Symbols:**

```
ffffffff8177e4d0-ffffffff8177e609: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8203a8a0)
Location: lib/radix-tree.c:876
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_replace_slot
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
```
**Symbols:**

```
ffffffff8203b0f0-ffffffff8203b225: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b8d10)
Location: lib/radix-tree.c:875
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_replace_slot
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
```
**Symbols:**

```
ffffffff820b95d0-ffffffff820b9703: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82193620)
Location: lib/radix-tree.c:875
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_replace_slot
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
```
**Symbols:**

```
ffffffff82193ee0-ffffffff82194013: __radix_tree_replace (STB_GLOBAL)
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
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8e910)
Location: lib/radix-tree.c:884
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
ffff800010d8e910-ffff800010d8ea1c: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e89038)
Location: lib/radix-tree.c:884
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
c0e89038-c0e8919c: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed15c0)
Location: lib/radix-tree.c:884
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
c000000000ed15c0-c000000000ed1728: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b733c)
Location: lib/radix-tree.c:884
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
ffffffe0008b733c-ffffffe0008b7428: __radix_tree_replace (STB_GLOBAL)
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
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a53230)
Location: lib/radix-tree.c:884
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
ffffffff81a53230-ffffffff81a53348: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a10330)
Location: lib/radix-tree.c:884
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
ffffffff81a10330-ffffffff81a10448: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf620)
Location: lib/radix-tree.c:884
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
ffffffff81abf620-ffffffff81abf738: __radix_tree_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __radix_tree_replace(struct xarray *root, struct xa_node *node, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acbaf0)
Location: lib/radix-tree.c:884
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_iter_replace
  - lib/radix-tree.c:radix_tree_replace_slot
```
**Symbols:**

```
ffffffff81acbaf0-ffffffff81acbc08: __radix_tree_replace (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void *private</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>radix_tree_update_node_t update_node</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root *root</code> ➡️ <code>struct xarray *root</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_node *node</code> ➡️ <code>struct xa_node *node</code>
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
