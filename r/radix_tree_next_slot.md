# Function: <code>radix_tree_next_slot</code>

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
In mm/filemap.c (ffffffff8118d0d0)
Location: include/linux/radix-tree.h:412
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_pages
```
```
In mm/shmem.c (ffffffff811a8886)
Location: include/linux/radix-tree.h:412
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/backing-dev.c (ffffffff811af877)
Location: include/linux/radix-tree.h:412
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In fs/fs-writeback.c (ffffffff8123a5ff)
Location: include/linux/radix-tree.h:412
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/radix-tree.c (ffffffff813ee76c)
Location: include/linux/radix-tree.h:412
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
In mm/filemap.c (ffffffff811a16c2)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/shmem.c (ffffffff811bf625)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811c8c6b)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8121c7d7)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff81262384)
Location: include/linux/radix-tree.h:466
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/radix-tree.c (ffffffff81434c2b)
Location: include/linux/radix-tree.h:466
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
In mm/filemap.c (ffffffff811b1535)
Location: include/linux/radix-tree.h:479
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/page-writeback.c (ffffffff811be0f2)
Location: include/linux/radix-tree.h:479
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811cfc1e)
Location: include/linux/radix-tree.h:479
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811d8d8b)
Location: include/linux/radix-tree.h:479
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8122e1ea)
Location: include/linux/radix-tree.h:479
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff81275862)
Location: include/linux/radix-tree.h:479
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/radix-tree.c (ffffffff814510d2)
Location: include/linux/radix-tree.h:479
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
In mm/filemap.c (ffffffff811b77d5)
Location: include/linux/radix-tree.h:523
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/page-writeback.c (ffffffff811c6311)
Location: include/linux/radix-tree.h:523
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811d93f0)
Location: include/linux/radix-tree.h:523
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811e1280)
Location: include/linux/radix-tree.h:523
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8123a4b8)
Location: include/linux/radix-tree.h:523
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff81282dbf)
Location: include/linux/radix-tree.h:523
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/idr.c (ffffffff818ecf7f)
Location: include/linux/radix-tree.h:523
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff818f0d24)
Location: include/linux/radix-tree.h:523
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
In mm/filemap.c (ffffffff811cbd55)
Location: include/linux/radix-tree.h:538
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
In mm/page-writeback.c (ffffffff811db131)
Location: include/linux/radix-tree.h:538
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811ee6c5)
Location: include/linux/radix-tree.h:538
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811f7290)
Location: include/linux/radix-tree.h:538
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff812591dc)
Location: include/linux/radix-tree.h:538
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff812a590f)
Location: include/linux/radix-tree.h:538
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:538
Inline: True
```
```
In lib/idr.c (ffffffff81972f9f)
Location: include/linux/radix-tree.h:538
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81977174)
Location: include/linux/radix-tree.h:538
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
In mm/filemap.c (ffffffff811ecf8a)
Location: include/linux/radix-tree.h:527
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
In mm/page-writeback.c (ffffffff811fc474)
Location: include/linux/radix-tree.h:527
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff81213b07)
Location: include/linux/radix-tree.h:527
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff812184dd)
Location: include/linux/radix-tree.h:527
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8127d603)
Location: include/linux/radix-tree.h:527
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff812941e5)
Location: include/linux/radix-tree.h:527
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/fs-writeback.c (ffffffff812cc4eb)
Location: include/linux/radix-tree.h:527
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:527
Inline: True
```
```
In lib/idr.c (ffffffff819cf579)
Location: include/linux/radix-tree.h:527
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff819d395e)
Location: include/linux/radix-tree.h:527
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
In mm/backing-dev.c (ffffffff8122b427)
Location: include/linux/radix-tree.h:416
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:416
Inline: True
```
```
In lib/idr.c (ffffffff81a08480)
Location: include/linux/radix-tree.h:416
Inline: True
Inline callers:
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81a0c925)
Location: include/linux/radix-tree.h:416
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
In mm/backing-dev.c (ffffffff8123b075)
Location: include/linux/radix-tree.h:403
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:403
Inline: True
```
```
In lib/idr.c (ffffffff81a77ee1)
Location: include/linux/radix-tree.h:403
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81a7c360)
Location: include/linux/radix-tree.h:403
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
In mm/backing-dev.c (ffffffff81249599)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:385
Inline: True
```
```
In lib/idr.c (ffffffff81aaf2c8)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81ab3690)
Location: include/linux/radix-tree.h:385
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
In mm/backing-dev.c (ffffffff81277240)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_unregister
```
```
In lib/idr.c (ffffffff815e8ff8)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff815ee8a1)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:385
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
In mm/backing-dev.c (ffffffff81281b30)
Location: include/linux/radix-tree.h:386
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_unregister
```
```
In lib/idr.c (ffffffff8160e0a8)
Location: include/linux/radix-tree.h:386
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81612ff1)
Location: include/linux/radix-tree.h:386
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:386
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
In mm/backing-dev.c (ffffffff81286f7b)
Location: include/linux/radix-tree.h:386
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In lib/idr.c (ffffffff815f17f8)
Location: include/linux/radix-tree.h:386
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff815f64d7)
Location: include/linux/radix-tree.h:386
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:386
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
In mm/backing-dev.c (ffffffff812c6537)
Location: include/linux/radix-tree.h:386
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In lib/idr.c (ffffffff8165e968)
Location: include/linux/radix-tree.h:386
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81663abb)
Location: include/linux/radix-tree.h:386
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:386
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
In mm/backing-dev.c (ffffffff813231e7)
Location: include/linux/radix-tree.h:388
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In lib/idr.c (ffffffff817781e8)
Location: include/linux/radix-tree.h:388
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff8177dc95)
Location: include/linux/radix-tree.h:388
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:388
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
In mm/backing-dev.c (ffffffff813979f7)
Location: include/linux/radix-tree.h:388
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:388
Inline: True
```
```
In lib/idr.c (ffffffff82020f48)
Location: include/linux/radix-tree.h:388
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff8203a406)
Location: include/linux/radix-tree.h:388
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
In mm/backing-dev.c (ffffffff813ca987)
Location: include/linux/radix-tree.h:397
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:397
Inline: True
```
```
In lib/idr.c (ffffffff820a0f68)
Location: include/linux/radix-tree.h:397
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff820b8865)
Location: include/linux/radix-tree.h:397
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
In mm/backing-dev.c (ffffffff813f53f7)
Location: include/linux/radix-tree.h:397
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:397
Inline: True
```
```
In lib/idr.c (ffffffff82178f48)
Location: include/linux/radix-tree.h:397
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff82193175)
Location: include/linux/radix-tree.h:397
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
In mm/backing-dev.c (ffff8000102decc8)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (ffff80001068d104)
Location: include/linux/radix-tree.h:385
Inline: True
```
```
In drivers/pinctrl/pinmux.c (ffff80001068fe7c)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e174)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (ffff800010d88b34)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffff800010d8dd48)
Location: include/linux/radix-tree.h:385
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
In mm/backing-dev.c (c0503c28)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (c082f1b0)
Location: include/linux/radix-tree.h:385
Inline: True
```
```
In drivers/pinctrl/pinmux.c (c0831c08)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (c0c61df0)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (c0e83a50)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (c0e88428)
Location: include/linux/radix-tree.h:385
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
In mm/backing-dev.c (c00000000039e5d8)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (c000000000825ea0)
Location: include/linux/radix-tree.h:385
Inline: True
```
```
In drivers/pinctrl/pinmux.c (c00000000082b600)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5ac10)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (c000000000ec9454)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (c000000000ed0638)
Location: include/linux/radix-tree.h:385
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
In mm/backing-dev.c (ffffffe0001f6b42)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/pinctrl/core.c (ffffffe0004992e4)
Location: include/linux/radix-tree.h:385
Inline: True
```
```
In drivers/pinctrl/pinmux.c (ffffffe00049ba64)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_generic_free_functions
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072c6f0)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/idr.c (ffffffe0008b2a18)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffe0008b6562)
Location: include/linux/radix-tree.h:385
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
In mm/backing-dev.c (ffffffff81241be9)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:385
Inline: True
```
```
In lib/idr.c (ffffffff81a4e118)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81a524e0)
Location: include/linux/radix-tree.h:385
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
In mm/backing-dev.c (ffffffff81234bd9)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:385
Inline: True
```
```
In lib/idr.c (ffffffff81a0b208)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81a0f5e0)
Location: include/linux/radix-tree.h:385
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
In mm/backing-dev.c (ffffffff8123f989)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:385
Inline: True
```
```
In lib/idr.c (ffffffff81aba508)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81abe8d0)
Location: include/linux/radix-tree.h:385
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
In mm/backing-dev.c (ffffffff8124f109)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:385
Inline: True
```
```
In lib/idr.c (ffffffff81ac6958)
Location: include/linux/radix-tree.h:385
Inline: True
Inline callers:
  - lib/idr.c:idr_get_next_ul
  - lib/idr.c:idr_for_each
```
```
In lib/radix-tree.c (ffffffff81acad70)
Location: include/linux/radix-tree.h:385
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
