# Function: <code>__radix_tree_iter_add</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a16c2)
Location: include/linux/radix-tree.h:416
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/shmem.c (ffffffff811bf6d3)
Location: include/linux/radix-tree.h:416
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811c8c6b)
Location: include/linux/radix-tree.h:416
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8121c7d7)
Location: include/linux/radix-tree.h:416
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff812623c2)
Location: include/linux/radix-tree.h:416
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/radix-tree.c (ffffffff81434c65)
Location: include/linux/radix-tree.h:416
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
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
In mm/filemap.c (ffffffff811b1535)
Location: include/linux/radix-tree.h:417
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/page-writeback.c (ffffffff811be0f2)
Location: include/linux/radix-tree.h:417
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811cfc1e)
Location: include/linux/radix-tree.h:417
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811d8d8b)
Location: include/linux/radix-tree.h:417
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8122e1ea)
Location: include/linux/radix-tree.h:417
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff8127587f)
Location: include/linux/radix-tree.h:417
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/radix-tree.c (ffffffff814510f6)
Location: include/linux/radix-tree.h:417
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:__radix_tree_next_slot
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
In mm/filemap.c (ffffffff811b77d5)
Location: include/linux/radix-tree.h:462
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/page-writeback.c (ffffffff811c6320)
Location: include/linux/radix-tree.h:462
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811d93f0)
Location: include/linux/radix-tree.h:462
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811e1280)
Location: include/linux/radix-tree.h:462
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8123a4b8)
Location: include/linux/radix-tree.h:462
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff81282ddf)
Location: include/linux/radix-tree.h:462
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/idr.c (ffffffff818ecf7f)
Location: include/linux/radix-tree.h:462
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff818f0d2e)
Location: include/linux/radix-tree.h:462
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:__radix_tree_next_slot
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
In mm/filemap.c (ffffffff811cbd55)
Location: include/linux/radix-tree.h:477
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff811db140)
Location: include/linux/radix-tree.h:477
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811ee6c8)
Location: include/linux/radix-tree.h:477
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811f7290)
Location: include/linux/radix-tree.h:477
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff812591df)
Location: include/linux/radix-tree.h:477
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff812a592f)
Location: include/linux/radix-tree.h:477
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:477
Inline: True
```
```
In lib/idr.c (ffffffff81972f9f)
Location: include/linux/radix-tree.h:477
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff8197717e)
Location: include/linux/radix-tree.h:477
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:__radix_tree_next_slot
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
In mm/filemap.c (ffffffff811ecfa3)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff811fc3f9)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff81213b22)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff812184fe)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8127d61e)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff81294200)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/fs-writeback.c (ffffffff812cc508)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:466
Inline: True
```
```
In lib/idr.c (ffffffff819cf59a)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff819d391a)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:skip_siblings
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
In mm/backing-dev.c (ffffffff8122b43c)
Location: include/linux/radix-tree.h:367
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:367
Inline: True
```
```
In lib/idr.c (ffffffff81a08495)
Location: include/linux/radix-tree.h:367
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81a0c909)
Location: include/linux/radix-tree.h:367
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
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
In mm/backing-dev.c (ffffffff8123b08a)
Location: include/linux/radix-tree.h:354
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:354
Inline: True
```
```
In lib/idr.c (ffffffff81a77f14)
Location: include/linux/radix-tree.h:354
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81a7c342)
Location: include/linux/radix-tree.h:354
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
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
In mm/backing-dev.c (ffffffff812495ae)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:336
Inline: True
```
```
In lib/idr.c (ffffffff81aaf2fb)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81ab3672)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
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
In mm/backing-dev.c (ffffffff81277255)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_unregister
```
```
In lib/idr.c (ffffffff815e9024)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff815ee883)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:336
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
In mm/backing-dev.c (ffffffff81281b45)
Location: include/linux/radix-tree.h:337
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_unregister
```
```
In lib/idr.c (ffffffff8160e0d4)
Location: include/linux/radix-tree.h:337
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81612fd3)
Location: include/linux/radix-tree.h:337
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:337
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
In mm/backing-dev.c (ffffffff81286f90)
Location: include/linux/radix-tree.h:337
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In lib/idr.c (ffffffff815f1824)
Location: include/linux/radix-tree.h:337
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff815f64b2)
Location: include/linux/radix-tree.h:337
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:337
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
In mm/backing-dev.c (ffffffff812c654c)
Location: include/linux/radix-tree.h:337
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In lib/idr.c (ffffffff8165e994)
Location: include/linux/radix-tree.h:337
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81663a96)
Location: include/linux/radix-tree.h:337
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:337
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
In mm/backing-dev.c (ffffffff81323203)
Location: include/linux/radix-tree.h:339
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In lib/idr.c (ffffffff817781fd)
Location: include/linux/radix-tree.h:339
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff8177dc6f)
Location: include/linux/radix-tree.h:339
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:339
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
In mm/backing-dev.c (ffffffff81397a13)
Location: include/linux/radix-tree.h:339
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:339
Inline: True
```
```
In lib/idr.c (ffffffff82020f5d)
Location: include/linux/radix-tree.h:339
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff8203a3e0)
Location: include/linux/radix-tree.h:339
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
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
In mm/backing-dev.c (ffffffff813ca9a3)
Location: include/linux/radix-tree.h:348
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:348
Inline: True
```
```
In lib/idr.c (ffffffff820a0f7d)
Location: include/linux/radix-tree.h:348
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff820b883f)
Location: include/linux/radix-tree.h:348
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
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
In mm/backing-dev.c (ffffffff813f5413)
Location: include/linux/radix-tree.h:348
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:348
Inline: True
```
```
In lib/idr.c (ffffffff82178f5d)
Location: include/linux/radix-tree.h:348
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff8219314f)
Location: include/linux/radix-tree.h:348
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
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
In mm/backing-dev.c (ffff8000102decdc)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (ffff80001068d118)
Location: include/linux/radix-tree.h:336
Inline: True
```
```
In drivers/pinctrl/pinmux.c (ffff80001068fe90)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e180)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (ffff800010d88b6c)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffff800010d8dd5c)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
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
In mm/backing-dev.c (c0503c3c)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (c082f1c4)
Location: include/linux/radix-tree.h:336
Inline: True
```
```
In drivers/pinctrl/pinmux.c (c0831c1c)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (c0c61dfc)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (c0e83a30)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (c0e89498)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_iter_resume
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
In mm/backing-dev.c (c00000000039e5fc)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (c000000000825ec4)
Location: include/linux/radix-tree.h:336
Inline: True
```
```
In drivers/pinctrl/pinmux.c (c00000000082b620)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5ac2c)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (c000000000ec94b0)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (c000000000ed0608)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
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
In mm/backing-dev.c (ffffffe0001f6b50)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (ffffffe0004992f2)
Location: include/linux/radix-tree.h:336
Inline: True
```
```
In drivers/pinctrl/pinmux.c (ffffffe00049ba72)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072c6f4)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (ffffffe0008b2a3c)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffe0008b6622)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
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
In mm/backing-dev.c (ffffffff81241bfe)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:336
Inline: True
```
```
In lib/idr.c (ffffffff81a4e14b)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81a524c2)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
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
In mm/backing-dev.c (ffffffff81234bee)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:336
Inline: True
```
```
In lib/idr.c (ffffffff81a0b23b)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81a0f5c2)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
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
In mm/backing-dev.c (ffffffff8123f99e)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:336
Inline: True
```
```
In lib/idr.c (ffffffff81aba53b)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81abe8b2)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
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
In mm/backing-dev.c (ffffffff8124f11e)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:336
Inline: True
```
```
In lib/idr.c (ffffffff81ac698b)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81acad52)
Location: include/linux/radix-tree.h:336
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_iter_resume
```
</details>
</li>
</ul>

## Differences
