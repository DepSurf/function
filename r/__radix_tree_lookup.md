# Function: <code>__radix_tree_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *__radix_tree_lookup(struct radix_tree_root *root, long unsigned int index, struct radix_tree_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813eef10)
Location: lib/radix-tree.c:491
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - lib/radix-tree.c:radix_tree_lookup_slot
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_delete_item
```
**Symbols:**

```
ffffffff813eef10-ffffffff813eefaa: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__radix_tree_lookup(struct radix_tree_root *root, long unsigned int index, struct radix_tree_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81435680)
Location: lib/radix-tree.c:677
Inline: False
Direct callers:
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_unlock_mapping_entry
  - fs/dax.c:get_unlocked_mapping_entry
  - lib/radix-tree.c:radix_tree_replace_clear_tags
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff81435680-ffffffff81435770: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__radix_tree_lookup(struct radix_tree_root *root, long unsigned int index, struct radix_tree_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81451e20)
Location: lib/radix-tree.c:911
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_radix_tree_replace
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:dax_invalidate_mapping_entry
  - fs/dax.c:dax_unlock_mapping_entry
  - fs/dax.c:get_unlocked_mapping_entry
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff81451e20-ffffffff81451f10: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct radix_tree_root *root, long unsigned int index, struct radix_tree_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f1cf0)
Location: lib/radix-tree.c:1029
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_radix_tree_replace
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_mapping_entry
  - fs/dax.c:get_unlocked_mapping_entry
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff818f1cf0-ffffffff818f1e14: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct radix_tree_root *root, long unsigned int index, struct radix_tree_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819781a0)
Location: lib/radix-tree.c:1028
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_radix_tree_replace
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_mapping_entry
  - fs/dax.c:get_unlocked_mapping_entry
  - lib/idr.c:idr_replace_ext
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff819781a0-ffffffff819782c4: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct radix_tree_root *root, long unsigned int index, struct radix_tree_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d48f0)
Location: lib/radix-tree.c:1029
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_radix_tree_replace
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:unlock_mapping_entry
  - fs/dax.c:__get_unlocked_mapping_entry
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff819d48f0-ffffffff819d49d4: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d5a0)
Location: lib/radix-tree.c:769
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff81a0d5a0-ffffffff81a0d63d: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7cee0)
Location: lib/radix-tree.c:756
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff81a7cee0-ffffffff81a7cf7d: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab4210)
Location: lib/radix-tree.c:756
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff81ab4210-ffffffff81ab42ad: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eeb90)
Location: lib/radix-tree.c:748
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff815eeb90-ffffffff815eec42: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff816132e0)
Location: lib/radix-tree.c:748
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff816132e0-ffffffff81613392: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f6940)
Location: lib/radix-tree.c:748
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff815f6940-ffffffff815f69f2: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:748
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff81cdf902-ffffffff81cdf95c: __radix_tree_lookup.cold (STB_LOCAL)
ffffffff81664020-ffffffff816640f4: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:748
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff81ea6092-ffffffff81ea60f8: __radix_tree_lookup.cold (STB_LOCAL)
ffffffff8177e260-ffffffff8177e352: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:748
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff820b7a0f-ffffffff820b7a75: __radix_tree_lookup.cold (STB_LOCAL)
ffffffff8203ae30-ffffffff8203af22: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:747
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff82138e7f-ffffffff82138ee1: __radix_tree_lookup.cold (STB_LOCAL)
ffffffff820b9320-ffffffff820b940f: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:747
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff8221ac24-ffffffff8221ac86: __radix_tree_lookup.cold (STB_LOCAL)
ffffffff82193c30-ffffffff82193d1f: __radix_tree_lookup (STB_GLOBAL)
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
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8e718)
Location: lib/radix-tree.c:756
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffff800010d8e718-ffff800010d8e7b0: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e88e08)
Location: lib/radix-tree.c:756
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
c0e88e08-c0e88eac: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed1330)
Location: lib/radix-tree.c:756
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
c000000000ed1330-c000000000ed13f0: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b719c)
Location: lib/radix-tree.c:756
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffe0008b719c-ffffffe0008b721c: __radix_tree_lookup (STB_GLOBAL)
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
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a53060)
Location: lib/radix-tree.c:756
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff81a53060-ffffffff81a530fd: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a10160)
Location: lib/radix-tree.c:756
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff81a10160-ffffffff81a101fd: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf450)
Location: lib/radix-tree.c:756
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff81abf450-ffffffff81abf4ed: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__radix_tree_lookup(const struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acb920)
Location: lib/radix-tree.c:756
Inline: False
Direct callers:
  - lib/idr.c:idr_replace
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_lookup
  - lib/radix-tree.c:radix_tree_lookup_slot
```
**Symbols:**

```
ffffffff81acb920-ffffffff81acb9bd: __radix_tree_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root *root</code> ➡️ <code>const struct radix_tree_root *root</code>
</li>
</ul>
</details>
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
<code>const struct radix_tree_root *root</code> ➡️ <code>const struct xarray *root</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_node **nodep</code> ➡️ <code>struct xa_node **nodep</code>
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
