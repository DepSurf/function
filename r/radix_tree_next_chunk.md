# Function: <code>radix_tree_next_chunk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void **radix_tree_next_chunk(struct radix_tree_root *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813ee4f0)
Location: lib/radix-tree.c:752
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_pages
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/backing-dev.c:bdi_unregister
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
```
**Symbols:**

```
ffffffff813ee4f0-ffffffff813ee716: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void **radix_tree_next_chunk(struct radix_tree_root *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81434480)
Location: lib/radix-tree.c:913
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/backing-dev.c:bdi_unregister
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff81434480-ffffffff814347a1: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void **radix_tree_next_chunk(struct radix_tree_root *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff814509f0)
Location: lib/radix-tree.c:1571
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/backing-dev.c:bdi_unregister
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff814509f0-ffffffff81450d29: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct radix_tree_root *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f0630)
Location: lib/radix-tree.c:1714
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/backing-dev.c:bdi_unregister
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_remove
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff818f0630-ffffffff818f0961: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct radix_tree_root *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81976a80)
Location: lib/radix-tree.c:1712
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/backing-dev.c:bdi_unregister
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_remove
  - lib/idr.c:idr_get_next_ext
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff81976a80-ffffffff81976db1: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct radix_tree_root *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3230)
Location: lib/radix-tree.c:1711
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/backing-dev.c:bdi_unregister
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_remove
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff819d3230-ffffffff819d3556: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0c430)
Location: lib/radix-tree.c:1176
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff81a0c430-ffffffff81a0c6d5: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7be90)
Location: lib/radix-tree.c:1163
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff81a7be90-ffffffff81a7c110: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab31c0)
Location: lib/radix-tree.c:1163
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff81ab31c0-ffffffff81ab3440: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815ee3a0)
Location: lib/radix-tree.c:1155
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff815ee3a0-ffffffff815ee63b: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81612ad0)
Location: lib/radix-tree.c:1155
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff81612ad0-ffffffff81612d8e: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f5fc0)
Location: lib/radix-tree.c:1156
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff815f5fc0-ffffffff815f626e: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1156
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff81cdf562-ffffffff81cdf721: radix_tree_next_chunk.cold (STB_LOCAL)
ffffffff816634d0-ffffffff8166383f: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1156
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff81ea5d22-ffffffff81ea5ec9: radix_tree_next_chunk.cold (STB_LOCAL)
ffffffff8177d5b0-ffffffff8177d98f: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1156
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff820b7691-ffffffff820b783c: radix_tree_next_chunk.cold (STB_LOCAL)
ffffffff82039cf0-ffffffff8203a0ce: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1154
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff82138b6b-ffffffff82138caa: radix_tree_next_chunk.cold (STB_LOCAL)
ffffffff820b80c0-ffffffff820b8521: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1154
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff8221a910-ffffffff8221aa4f: radix_tree_next_chunk.cold (STB_LOCAL)
ffffffff821929d0-ffffffff82192e31: radix_tree_next_chunk (STB_GLOBAL)
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
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8d840)
Location: lib/radix-tree.c:1163
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffff800010d8d840-ffff800010d8da98: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e87e34)
Location: lib/radix-tree.c:1163
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
c0e87e34-c0e8816c: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ecfec0)
Location: lib/radix-tree.c:1163
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
c000000000ecfec0-c000000000ed0234: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b60d2)
Location: lib/radix-tree.c:1163
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffe0008b60d2-ffffffe0008b6362: radix_tree_next_chunk (STB_GLOBAL)
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
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a52010)
Location: lib/radix-tree.c:1163
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff81a52010-ffffffff81a52290: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0f110)
Location: lib/radix-tree.c:1163
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff81a0f110-ffffffff81a0f390: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abe400)
Location: lib/radix-tree.c:1163
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff81abe400-ffffffff81abe680: radix_tree_next_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void **radix_tree_next_chunk(const struct xarray *root, struct radix_tree_iter *iter, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81aca8a0)
Location: lib/radix-tree.c:1163
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
**Symbols:**

```
ffffffff81aca8a0-ffffffff81acab20: radix_tree_next_chunk (STB_GLOBAL)
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
