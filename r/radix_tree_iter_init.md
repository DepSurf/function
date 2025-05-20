# Function: <code>radix_tree_iter_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118d04a)
Location: include/linux/radix-tree.h:341
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_pages
```
```
In mm/shmem.c (ffffffff811a8806)
Location: include/linux/radix-tree.h:341
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/backing-dev.c (ffffffff811af85d)
Location: include/linux/radix-tree.h:341
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In fs/fs-writeback.c (ffffffff8123a5d5)
Location: include/linux/radix-tree.h:341
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/radix-tree.c (ffffffff813ee74f)
Location: include/linux/radix-tree.h:341
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a16d3)
Location: include/linux/radix-tree.h:367
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/shmem.c (ffffffff811bf604)
Location: include/linux/radix-tree.h:367
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811c8c70)
Location: include/linux/radix-tree.h:367
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8121c63c)
Location: include/linux/radix-tree.h:367
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff81262335)
Location: include/linux/radix-tree.h:367
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/radix-tree.c (ffffffff81434c04)
Location: include/linux/radix-tree.h:367
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b1543)
Location: include/linux/radix-tree.h:368
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/page-writeback.c (ffffffff811be11b)
Location: include/linux/radix-tree.h:368
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811cfc40)
Location: include/linux/radix-tree.h:368
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811d8d90)
Location: include/linux/radix-tree.h:368
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8122e06d)
Location: include/linux/radix-tree.h:368
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff81275838)
Location: include/linux/radix-tree.h:368
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/radix-tree.c (ffffffff814510dc)
Location: include/linux/radix-tree.h:368
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b77e3)
Location: include/linux/radix-tree.h:377
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/page-writeback.c (ffffffff811c6301)
Location: include/linux/radix-tree.h:377
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811d936b)
Location: include/linux/radix-tree.h:377
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811e1285)
Location: include/linux/radix-tree.h:377
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8123a35e)
Location: include/linux/radix-tree.h:377
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff81282d7b)
Location: include/linux/radix-tree.h:377
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/idr.c (ffffffff818ecf89)
Location: include/linux/radix-tree.h:377
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_remove
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc
```
```
In lib/radix-tree.c (ffffffff818f0d14)
Location: include/linux/radix-tree.h:377
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cbd63)
Location: include/linux/radix-tree.h:392
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff811db121)
Location: include/linux/radix-tree.h:392
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811ee64c)
Location: include/linux/radix-tree.h:392
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811f7295)
Location: include/linux/radix-tree.h:392
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff81259092)
Location: include/linux/radix-tree.h:392
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff812a58cb)
Location: include/linux/radix-tree.h:392
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:392
Inline: True
```
```
In lib/idr.c (ffffffff81972fa9)
Location: include/linux/radix-tree.h:392
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_remove
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_get_next_ext
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_cmn
```
```
In lib/radix-tree.c (ffffffff81977164)
Location: include/linux/radix-tree.h:392
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ece67)
Location: include/linux/radix-tree.h:381
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff811fc3d8)
Location: include/linux/radix-tree.h:381
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff81213ad4)
Location: include/linux/radix-tree.h:381
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff812184c2)
Location: include/linux/radix-tree.h:381
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8127d430)
Location: include/linux/radix-tree.h:381
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff812941a8)
Location: include/linux/radix-tree.h:381
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/fs-writeback.c (ffffffff812cc4b1)
Location: include/linux/radix-tree.h:381
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:381
Inline: True
```
```
In lib/idr.c (ffffffff819cf558)
Location: include/linux/radix-tree.h:381
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_remove
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff819d3904)
Location: include/linux/radix-tree.h:381
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122b40c)
Location: include/linux/radix-tree.h:282
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:282
Inline: True
```
```
In lib/idr.c (ffffffff81a085c1)
Location: include/linux/radix-tree.h:282
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff81a0c8f4)
Location: include/linux/radix-tree.h:282
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123b05a)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In lib/idr.c (ffffffff81a77f71)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff81a7c335)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124957e)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In lib/idr.c (ffffffff81aaf263)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff81ab3665)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81277226)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_unregister
```
```
In lib/idr.c (ffffffff815e8f93)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff815ee875)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81281b16)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_unregister
```
```
In lib/idr.c (ffffffff8160e043)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff81612fc5)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:270
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81286f61)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In lib/idr.c (ffffffff815f1793)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff815f64a5)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:270
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c651d)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In lib/idr.c (ffffffff8165e903)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff81663a81)
Location: include/linux/radix-tree.h:270
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:270
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813231cd)
Location: include/linux/radix-tree.h:272
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In lib/idr.c (ffffffff81778168)
Location: include/linux/radix-tree.h:272
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff8177dc4f)
Location: include/linux/radix-tree.h:272
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:272
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813979dd)
Location: include/linux/radix-tree.h:272
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:272
Inline: True
```
```
In lib/idr.c (ffffffff82020ec8)
Location: include/linux/radix-tree.h:272
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff8203a3ca)
Location: include/linux/radix-tree.h:272
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813ca96d)
Location: include/linux/radix-tree.h:281
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:281
Inline: True
```
```
In lib/idr.c (ffffffff820a0ee8)
Location: include/linux/radix-tree.h:281
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff820b881f)
Location: include/linux/radix-tree.h:281
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f53dd)
Location: include/linux/radix-tree.h:281
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:281
Inline: True
```
```
In lib/idr.c (ffffffff82178ec8)
Location: include/linux/radix-tree.h:281
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff8219312f)
Location: include/linux/radix-tree.h:281
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102decac)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (ffff80001068d0f0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In drivers/pinctrl/pinmux.c (ffff80001068fe5c)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e128)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (ffff800010d88ad0)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffff800010d8dd10)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c0503c0c)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (c082f190)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In drivers/pinctrl/pinmux.c (c0831be4)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (c0c61db8)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (c0e839ac)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (c0e883dc)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039e5c0)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (c000000000825e78)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In drivers/pinctrl/pinmux.c (c00000000082b5d8)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5abc4)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (c000000000ec93b8)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (c000000000ed05ac)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f6b24)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (ffffffe0004992c8)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In drivers/pinctrl/pinmux.c (ffffffe00049ba46)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072c6b4)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (ffffffe0008b29c6)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffe0008b6562)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81241bce)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In lib/idr.c (ffffffff81a4e0b3)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff81a524b5)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81234bbe)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In lib/idr.c (ffffffff81a0b1a3)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff81a0f5b5)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123f96e)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In lib/idr.c (ffffffff81aba4a3)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff81abe8a5)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124f0ee)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In lib/idr.c (ffffffff81ac68f3)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff81acad45)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
</details>
</li>
</ul>

## Differences
